
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="18.68 7.23 18.68 22.5 5.32 22.5 5.32 7.23"/><path class="cls-1" d="M18.68,17.73H22.5V7.23A5.72,5.72,0,0,0,16.77,1.5H7.23A5.72,5.72,0,0,0,1.5,7.23v10.5H5.32"/><line class="cls-1" x1="5.32" y1="15.82" x2="18.68" y2="15.82"/><line class="cls-1" x1="10.09" y1="19.64" x2="12" y2="15.82"/><line class="cls-1" x1="13.91" y1="19.64" x2="12" y2="15.82"/><line class="cls-1" x1="15.82" y1="1.5" x2="5.32" y2="15.82"/><line class="cls-1" x1="12" y1="6.7" x2="8.18" y2="1.5"/></svg>
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