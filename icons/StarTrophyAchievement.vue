
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="12 8.18 12.46 9.12 13.51 9.28 12.75 10.01 12.93 11.04 12 10.56 11.07 11.04 11.25 10.01 10.49 9.28 11.54 9.12 12 8.18"/><path class="cls-2" d="M17.73,22.5c-3.82,0-5.73-1.91-5.73-3.82s5.73-3.82,5.73-7.63S15.82,1.5,15.82,1.5H8.18S6.27,7.23,6.27,11.05,12,16.77,12,18.68,10.09,22.5,6.27,22.5"/><line class="cls-2" x1="6.27" y1="22.5" x2="17.73" y2="22.5"/><path class="cls-2" d="M16.77,4.36a3.54,3.54,0,0,1,2.87-1.91A2.53,2.53,0,0,1,22.5,5.32c0,1.91-4.77,3.48-4.77,5.73A1.87,1.87,0,0,0,19.64,13"/><path class="cls-2" d="M7.23,4.36A3.54,3.54,0,0,0,4.36,2.45,2.53,2.53,0,0,0,1.5,5.32c0,1.91,4.77,3.48,4.77,5.73A1.87,1.87,0,0,1,4.36,13"/></svg>
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
    .cls-1,.cls-2{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-1{stroke-linecap:square;}
</style>