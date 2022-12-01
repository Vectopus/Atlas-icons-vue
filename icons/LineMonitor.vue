
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="1.5" width="21" height="16.23" rx="1.91"/><line class="cls-1" x1="12" y1="22.5" x2="12" y2="17.73"/><line class="cls-1" x1="16.77" y1="22.5" x2="7.23" y2="22.5"/><polyline class="cls-2" points="8.18 11.04 11.04 8.18 12.96 10.09 15.82 7.23"/></svg>
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
    .cls-1,.cls-2{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-2{stroke-linecap:square;}
</style>