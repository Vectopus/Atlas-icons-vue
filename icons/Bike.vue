
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M6.82,13.27A3.77,3.77,0,0,0,5.32,13a3.82,3.82,0,1,0,3.82,3.82"/><circle class="cls-1" cx="18.68" cy="16.77" r="3.82"/><path class="cls-1" d="M15.82,3.41h2.47a1.35,1.35,0,0,1,1.35,1.35h0a1.35,1.35,0,0,1-.4,1L17.73,7.23l.95,9.54"/><polyline class="cls-1" points="17.73 10.09 15.82 10.09 11.04 16.77 5.32 16.77 9.14 10.09 11.04 16.77"/><line class="cls-1" x1="9.14" y1="6.27" x2="9.14" y2="10.09"/><line class="cls-1" x1="7.23" y1="6.27" x2="12" y2="6.27"/><line class="cls-1" x1="9.14" y1="10.09" x2="15.82" y2="10.09"/></svg>
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