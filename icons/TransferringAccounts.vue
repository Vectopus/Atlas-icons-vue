
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="19.65" cy="16.8" r="1.91"/><path class="cls-1" d="M1.48,10.11A2.86,2.86,0,0,1,4.35,7.24h0a2.87,2.87,0,0,1,2.87,2.87"/><path class="cls-1" d="M16.78,23.5a2.88,2.88,0,0,1,2.87-2.87h0a2.87,2.87,0,0,1,2.87,2.87"/><circle class="cls-1" cx="4.35" cy="3.41" r="1.91"/><path class="cls-1" d="M10.09,2.46h5.74a3.82,3.82,0,0,1,3.82,3.82v4.79"/><polyline class="cls-1" points="22.52 8.2 19.65 11.06 16.78 8.2"/><path class="cls-1" d="M13.91,21.59H8.17a3.83,3.83,0,0,1-3.82-3.83V13"/><polyline class="cls-1" points="1.48 15.85 4.35 12.98 7.22 15.85"/></svg>
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