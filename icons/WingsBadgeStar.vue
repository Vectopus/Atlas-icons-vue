
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="12" r="5.73"/><polygon class="cls-1" points="12 10.09 12.62 11.35 14.01 11.55 13 12.53 13.24 13.91 12 13.26 10.76 13.91 11 12.53 9.99 11.55 11.38 11.35 12 10.09"/><path class="cls-2" d="M17.39,12h4.16V13a2.86,2.86,0,0,1-2.87,2.87H16.77"/><path class="cls-1" d="M6.27,12H2.45V13a2.86,2.86,0,0,0,2.87,2.87H7.23"/><path class="cls-2" d="M16.26,8.18H22.5v1A2.86,2.86,0,0,1,19.64,12H17.73"/><path class="cls-2" d="M7.74,8.18H1.5v1A2.86,2.86,0,0,0,4.36,12H6.27"/></svg>
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