
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="20.59 1.5 20.59 6.27 15.82 6.27"/><polyline class="cls-1" points="3.41 22.5 3.41 17.73 8.18 17.73"/><polyline class="cls-1" points="22.5 20.59 17.73 20.59 17.73 15.82"/><polyline class="cls-1" points="1.5 3.41 6.27 3.41 6.27 8.18"/><path class="cls-1" d="M9.24,1.87A10.1,10.1,0,0,1,12,1.5,10.49,10.49,0,0,1,20.59,6"/><path class="cls-1" d="M1.87,14.76A10.1,10.1,0,0,1,1.5,12,10.49,10.49,0,0,1,6,3.41"/><path class="cls-1" d="M3.41,18A10.49,10.49,0,0,0,12,22.5a10.1,10.1,0,0,0,2.76-.37"/><path class="cls-1" d="M22.13,9.24A10.1,10.1,0,0,1,22.5,12,10.49,10.49,0,0,1,18,20.59"/></svg>
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