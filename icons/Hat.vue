
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M21,17.07l-5.27,1.17a17.09,17.09,0,0,1-3.77.42h0a17.09,17.09,0,0,1-3.77-.42L3,17.07A1.86,1.86,0,0,1,1.5,15.26h0a1.86,1.86,0,0,1,2.27-1.82l4.46,1a17.7,17.7,0,0,0,3.77.41h0a17.7,17.7,0,0,0,3.77-.41l4.46-1a1.86,1.86,0,0,1,2.27,1.82h0A1.86,1.86,0,0,1,21,17.07Z"/><path class="cls-1" d="M5.34,10l2.89.64A17.7,17.7,0,0,0,12,11a17.7,17.7,0,0,0,3.77-.41L18.66,10"/><path class="cls-1" d="M4.73,13.65l1.2-7.23A2.48,2.48,0,0,1,8.38,4.34a2.45,2.45,0,0,1,1.39.42L12,6.25l2.23-1.49a2.45,2.45,0,0,1,1.39-.42,2.49,2.49,0,0,1,1.61.59,2.46,2.46,0,0,1,.84,1.49l1.2,7.23"/></svg>
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