
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M1.5,18.68H3.41l5,2.87A7.22,7.22,0,0,0,12,22.5h0"/><polyline class="cls-1" points="19.16 19.5 20.59 18.68 22.5 18.68"/><path class="cls-1" d="M12,22.5a7.12,7.12,0,0,0,3.57-.95l2-1.16-3.68-5.53-2.64.66a3.08,3.08,0,0,1-.8.1A3.27,3.27,0,0,1,9,15.27a1.48,1.48,0,0,1-.83-1.33,1.5,1.5,0,0,1,.91-1.38l5.07-2.16a3.7,3.7,0,0,1,1.48-.31,3.74,3.74,0,0,1,2.08.63L19.64,12H22.5"/><path class="cls-1" d="M1.5,12H4.36l1.92-1.28a3.74,3.74,0,0,1,2.08-.63,3.7,3.7,0,0,1,1.48.31l2.16.92"/><line class="cls-1" x1="22.5" y1="10.09" x2="22.5" y2="20.59"/><line class="cls-1" x1="1.5" y1="10.09" x2="1.5" y2="20.59"/><polyline class="cls-1" points="8.18 3.41 11.04 6.27 15.82 1.5"/></svg>
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