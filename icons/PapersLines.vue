
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="6.27" y="1.5" width="15.27" height="17.18"/><polyline class="cls-1" points="17.73 18.68 17.73 22.5 2.46 22.5 2.46 5.32 6.27 5.32"/><line class="cls-1" x1="9.14" y1="6.27" x2="18.68" y2="6.27"/><line class="cls-1" x1="9.14" y1="10.09" x2="18.68" y2="10.09"/><line class="cls-1" x1="9.14" y1="13.91" x2="14.86" y2="13.91"/></svg>
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