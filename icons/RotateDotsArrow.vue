
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12,1.5A10.52,10.52,0,1,1,3.39,18.07"/><line class="cls-2" x1="1.48" y1="12.02" x2="1.48" y2="12.02"/><path class="cls-3" d="M2.28,8A10.51,10.51,0,0,1,10,1.7"/><line class="cls-2" x1="12" y1="1.5" x2="12" y2="1.5"/><polyline class="cls-1" points="3.39 23.5 3.39 17.76 9.13 17.76"/></svg>
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
    .cls-1,.cls-2,.cls-3{fill:none;stroke:currentColor;}.cls-1{stroke-miterlimit:10;}.cls-2,.cls-3{stroke-linecap:round;stroke-linejoin:round;}.cls-3{stroke-dasharray:0 4.13;}
</style>