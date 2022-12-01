
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M17.6,17.81a28.35,28.35,0,0,0-3.73-.41"/><path class="cls-1" d="M10.13,17.4a28.35,28.35,0,0,0-3.73.41"/><line class="cls-1" x1="22.26" y1="20.15" x2="22.26" y2="8.96"/><line class="cls-1" x1="1.74" y1="20.15" x2="1.74" y2="8.96"/><path class="cls-1" d="M22.26,20.15c0,1-1.86,1.85-4.66,2.35V11.31c2.8-.5,4.66-1.36,4.66-2.35,0-1.37-3.62-2.51-8.39-2.75"/><path class="cls-1" d="M10.13,6.21C5.36,6.45,1.74,7.59,1.74,9c0,1,1.86,1.85,4.66,2.35V22.5c-2.8-.5-4.66-1.36-4.66-2.35"/><line class="cls-1" x1="12" y1="1.5" x2="12" y2="3.37"/><line class="cls-1" x1="12" y1="5.23" x2="12" y2="7.1"/><line class="cls-1" x1="12" y1="8.96" x2="12" y2="10.83"/><line class="cls-1" x1="12" y1="12.69" x2="12" y2="14.56"/><line class="cls-1" x1="12" y1="20.15" x2="12" y2="22.02"/><line class="cls-1" x1="12" y1="16.42" x2="12" y2="18.29"/></svg>
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