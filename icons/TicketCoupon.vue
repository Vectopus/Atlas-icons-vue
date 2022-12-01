
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="coupon"><path class="cls-1" d="M22.5,4.36V19.64H1.5V14.86a2.86,2.86,0,0,0,0-5.72V4.36Z"/><path class="cls-2" d="M19.64,8.18h0Z"/><path class="cls-2" d="M19.64,12h0Z"/><line class="cls-2" x1="8.18" y1="8.18" x2="10.09" y2="8.18"/><line class="cls-2" x1="8.18" y1="12" x2="10.09" y2="12"/><line class="cls-2" x1="8.18" y1="15.82" x2="10.09" y2="15.82"/></g></svg>
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