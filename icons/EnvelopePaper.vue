
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="5.32 12 5.32 1.5 18.68 1.5 18.68 12"/><line class="cls-1" x1="8.18" y1="6.27" x2="15.82" y2="6.27"/><line class="cls-1" x1="8.18" y1="10.09" x2="15.82" y2="10.09"/><polyline class="cls-1" points="5.32 3.41 1.5 7.23 1.5 8.18 1.5 22.5 22.5 22.5 22.5 8.18 22.5 7.23 18.68 3.41"/><polyline class="cls-1" points="1.5 8.18 12 18.68 22.5 8.18"/></svg>
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