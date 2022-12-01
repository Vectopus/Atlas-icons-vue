
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="4.36" width="21" height="15.27"/><polyline class="cls-1" points="1.5 4.36 12 14.86 22.5 4.36"/><line class="cls-1" x1="9.14" y1="12" x2="1.5" y2="19.64"/><line class="cls-1" x1="22.5" y1="19.64" x2="14.86" y2="12"/><rect class="cls-1" x="1.5" y="4.36" width="21" height="15.27"/></svg>
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