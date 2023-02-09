
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="15.82 6.32 12 2.5 8.18 6.32"/><line class="cls-1" x1="12" y1="2.5" x2="12" y2="23.5"/><polyline class="cls-1" points="9.14 13 5.32 9.18 1.5 13"/><line class="cls-1" x1="5.32" y1="9.18" x2="5.32" y2="23.5"/><polyline class="cls-1" points="22.5 13 18.68 9.18 14.86 13"/><line class="cls-1" x1="18.68" y1="9.18" x2="18.68" y2="23.5"/></svg>
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