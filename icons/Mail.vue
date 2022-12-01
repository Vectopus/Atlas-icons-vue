
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="4.36" width="21" height="15.27"/><polyline class="cls-1" points="18.68 4.36 12 9.14 5.32 4.36"/><polyline class="cls-1" points="22.5 6.27 12 13.91 1.5 6.27"/><line class="cls-1" x1="18.68" y1="4.36" x2="5.32" y2="4.36"/><polyline class="cls-1" points="18.68 9.05 18.68 19.64 5.32 19.64 5.32 9.05"/></svg>
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