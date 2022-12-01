
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="17.73 1.5 12 7.23 9.14 4.36"/><polyline class="cls-1" points="16.68 7.23 22.5 7.23 22.5 22.5 1.5 22.5 1.5 7.23 7.32 7.23"/><polyline class="cls-1" points="1.5 7.23 12 17.73 22.5 7.23"/><line class="cls-1" x1="9.14" y1="14.86" x2="1.5" y2="22.5"/><line class="cls-1" x1="22.5" y1="22.5" x2="14.86" y2="14.86"/><polyline class="cls-1" points="16.68 7.23 22.5 7.23 22.5 22.5 1.5 22.5 1.5 7.23 7.32 7.23"/></svg>
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