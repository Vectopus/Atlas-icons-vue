
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12,5.32c1.91,0,2.86-2.24,2.86-3.82h1.91s0,5.73,2.87,7.64V22.5H12"/><path class="cls-1" d="M12,22.5H4.36V9.14C7.23,7.23,7.23,1.5,7.23,1.5H9.14c0,1.58.95,3.82,2.86,3.82"/><polyline class="cls-2" points="12 15.82 12 9.14 10.09 11.04"/><line class="cls-1" x1="10.09" y1="15.82" x2="13.91" y2="15.82"/></svg>
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