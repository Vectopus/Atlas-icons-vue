
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M1.5,14.89H3.41l5,2.87A7.21,7.21,0,0,0,12,18.7h0"/><polyline class="cls-1" points="19.16 15.71 20.59 14.89 22.5 14.89"/><path class="cls-1" d="M12,18.7a7.21,7.21,0,0,0,3.57-.94l2-1.17-3.68-5.52-2.65.66a3.42,3.42,0,0,1-.79.09A3.26,3.26,0,0,1,9,11.48a1.49,1.49,0,0,1,.08-2.71L14.16,6.6a3.77,3.77,0,0,1,3.56.33L19.64,8.2H22.5"/><path class="cls-1" d="M1.5,8.2H4.36L6.28,6.93A3.77,3.77,0,0,1,9.84,6.6L12,7.53"/><line class="cls-1" x1="22.5" y1="6.3" x2="22.5" y2="16.8"/><line class="cls-1" x1="1.5" y1="6.3" x2="1.5" y2="16.8"/></svg>
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