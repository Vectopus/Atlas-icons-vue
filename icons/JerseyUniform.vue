
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="18.68 7.23 18.68 22.5 5.32 22.5 5.32 7.23"/><path class="cls-1" d="M5.32,12H1.5V8A6.52,6.52,0,0,1,3.41,3.41h0A6.52,6.52,0,0,1,8,1.5H9.14c0,1,1.28,1.91,2.86,1.91s2.86-.86,2.86-1.91H16a6.52,6.52,0,0,1,4.61,1.91h0A6.52,6.52,0,0,1,22.5,8v4H18.68"/><polyline class="cls-2" points="12 15.82 12 9.14 10.09 11.04"/><line class="cls-1" x1="10.09" y1="15.82" x2="13.91" y2="15.82"/></svg>
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
    .cls-1,.cls-2{fill:none;stroke:currentColor;}.cls-1{stroke-miterlimit:10;}.cls-2{stroke-linejoin:bevel;}
</style>