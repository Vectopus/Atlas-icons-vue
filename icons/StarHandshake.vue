
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M1.5,18.73H3.41l5,2.87a7.22,7.22,0,0,0,3.57.95h0"/><polyline class="cls-1" points="19.16 19.55 20.59 18.73 22.5 18.73"/><path class="cls-1" d="M12,22.55a7.22,7.22,0,0,0,3.57-.95l2-1.16-3.68-5.53-2.65.66a3.42,3.42,0,0,1-.79.09A3.26,3.26,0,0,1,9,15.32a1.49,1.49,0,0,1,.08-2.71l5.07-2.17a3.69,3.69,0,0,1,1.48-.3,3.74,3.74,0,0,1,2.08.63l1.92,1.28H22.5"/><path class="cls-1" d="M1.5,12.05H4.36l1.92-1.28a3.74,3.74,0,0,1,2.08-.63,3.69,3.69,0,0,1,1.48.3l2.16.93"/><line class="cls-1" x1="22.5" y1="10.14" x2="22.5" y2="20.64"/><line class="cls-1" x1="1.5" y1="10.14" x2="1.5" y2="20.64"/><polygon class="cls-1" points="12 3.46 12.46 4.4 13.51 4.55 12.75 5.28 12.93 6.32 12 5.83 11.07 6.32 11.25 5.28 10.49 4.55 11.54 4.4 12 3.46"/></svg>
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