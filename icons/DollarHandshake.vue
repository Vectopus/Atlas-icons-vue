
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M1.48,18.67H3.39l5,2.88A7.2,7.2,0,0,0,12,22.5h0"/><polyline class="cls-1" points="19.17 19.5 20.61 18.67 22.52 18.67"/><path class="cls-1" d="M12,22.5a7.26,7.26,0,0,0,3.58-.95l2-1.16-3.7-5.54-2.65.66a3.42,3.42,0,0,1-.79.09A3.23,3.23,0,0,1,9,15.26a1.5,1.5,0,0,1-.84-1.34,1.52,1.52,0,0,1,.91-1.38l5.08-2.17a3.79,3.79,0,0,1,3.57.33L19.65,12h2.87"/><path class="cls-1" d="M1.48,12H4.35L6.27,10.7a3.79,3.79,0,0,1,3.57-.33L12,11.3"/><line class="cls-1" x1="22.52" y1="10.07" x2="22.52" y2="20.59"/><line class="cls-1" x1="1.48" y1="10.07" x2="1.48" y2="20.59"/><path class="cls-1" d="M14.87,2.41H11.16a1.07,1.07,0,0,0-1.07,1.08h0a1.07,1.07,0,0,0,.81,1l2.2.55a1.07,1.07,0,0,1,.81,1h0A1.08,1.08,0,0,1,12.84,7.2H9.13"/><line class="cls-1" x1="12" y1="0.5" x2="12" y2="2.41"/><line class="cls-1" x1="12" y1="7.2" x2="12" y2="9.11"/></svg>
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