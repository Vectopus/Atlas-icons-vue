
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M22.52,13.93V10.11H20.39a8.47,8.47,0,0,0-1.11-2.66l1.51-1.52-2.7-2.7L16.58,4.74a8.63,8.63,0,0,0-2.67-1.11V1.5H10.09V3.63A8.63,8.63,0,0,0,7.42,4.74L5.91,3.23l-2.7,2.7L4.72,7.45a8.47,8.47,0,0,0-1.11,2.66H1.48v3.82"/><path class="cls-1" d="M16.78,23.5a2.88,2.88,0,0,1,2.87-2.87h0a2.87,2.87,0,0,1,2.87,2.87"/><circle class="cls-1" cx="19.65" cy="16.8" r="1.91"/><path class="cls-1" d="M1.48,23.5a2.87,2.87,0,0,1,2.87-2.87h0A2.88,2.88,0,0,1,7.22,23.5"/><circle class="cls-1" cx="4.35" cy="16.8" r="1.91"/><path class="cls-1" d="M15.83,12a3.83,3.83,0,0,0-7.66,0"/><path class="cls-1" d="M9.13,23.5V21.59A2.87,2.87,0,0,1,12,18.72h0a2.87,2.87,0,0,1,2.87,2.87V23.5"/><circle class="cls-1" cx="12" cy="14.89" r="1.91"/></svg>
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