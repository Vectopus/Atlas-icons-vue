
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="14.89 18.68 14.89 22.5 2.48 22.5 2.48 1.5 14.89 1.5 14.89 5.32"/><line class="cls-1" x1="22.52" y1="12" x2="9.16" y2="12"/><polyline class="cls-1" points="13.93 7.23 9.16 12 13.93 16.77"/></svg>
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