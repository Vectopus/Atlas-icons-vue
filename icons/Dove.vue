
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M20.57,6.27v6.92a9.31,9.31,0,0,1-9.31,9.31h-.48a9.3,9.3,0,0,1-9.3-9.31V13H7.2A3.81,3.81,0,0,0,11,9.14V6.27A4.78,4.78,0,0,1,15.8,1.5h0A4.78,4.78,0,0,1,20.57,6.27Z"/><path class="cls-1" d="M11,9.14V13a4.77,4.77,0,0,1-4.77,4.78h0A4.77,4.77,0,0,1,1.48,13"/><polyline class="cls-1" points="20.57 7.23 21.52 8.18 20.57 8.18"/><circle class="cls-2" cx="17.7" cy="6.27" r="0.95"/></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-2{fill:currentColor;}
</style>