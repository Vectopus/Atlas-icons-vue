
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="18.68 6.97 22.5 10.09 22.5 22.5 1.5 22.5 1.5 10.09 5.32 6.97"/><polyline class="cls-1" points="1.5 11.04 12 18.68 22.5 11.04"/><polyline class="cls-1" points="5.32 13.91 5.32 1.5 18.68 1.5 18.68 13.91"/><line class="cls-1" x1="8.18" y1="5.32" x2="15.82" y2="5.32"/><line class="cls-1" x1="8.18" y1="9.14" x2="15.82" y2="9.14"/><line class="cls-1" x1="8.18" y1="12.95" x2="15.82" y2="12.95"/></svg>
</template>
<script>
    export default {
        props: {
            size: {
                type: Number,
                default: 24,
                required: false,
            },
            weight: {
                type: Number,
                default: 2,
                required: false,
            },
        }
    }
</script>
<style scoped>
    .cls-1{fill:none;stroke:currentColor;stroke-miterlimit:10;}
</style>