
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="13.91 13.91 22.5 13.91 22.5 1.5 13.91 1.5 1.5 1.5 1.5 13.91 9.14 13.91 9.14 15.82"/><polyline class="cls-1" points="6.27 22.5 1.5 22.5 1.5 13.91 1.5 1.5 13.91 1.5 13.91 6.27 12 6.27"/><polyline class="cls-1" points="13.91 10.09 13.91 13.91 13.91 22.5 9.14 22.5"/><line class="cls-1" x1="18.68" y1="7.23" x2="22.5" y2="7.23"/></svg>
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