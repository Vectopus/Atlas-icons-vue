
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M8.18,15.82A3.82,3.82,0,0,1,12,12h0a3.82,3.82,0,0,1,3.82,3.82"/><circle class="cls-1" cx="12" cy="8.66" r="2.39"/><polyline class="cls-1" points="21.55 6.27 17.73 6.27 17.73 2.46"/><line class="cls-1" x1="22.5" y1="1.5" x2="17.73" y2="6.27"/><polyline class="cls-1" points="2.46 17.73 6.27 17.73 6.27 21.55"/><line class="cls-1" x1="1.5" y1="22.5" x2="6.27" y2="17.73"/><polyline class="cls-1" points="17.73 21.55 17.73 17.73 21.55 17.73"/><line class="cls-1" x1="22.5" y1="22.5" x2="17.73" y2="17.73"/><polyline class="cls-1" points="6.27 2.46 6.27 6.27 2.46 6.27"/><line class="cls-1" x1="1.5" y1="1.5" x2="6.27" y2="6.27"/></svg>
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