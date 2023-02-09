
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M22.5,12c0,.9-1.1,1.64-1.32,2.46s.35,2.05-.08,2.79-1.77.85-2.38,1.47-.71,1.94-1.47,2.37-1.94-.14-2.79.09S12.89,22.5,12,22.5s-1.63-1.1-2.46-1.32-2,.35-2.79-.09-.85-1.76-1.47-2.37S3.34,18,2.9,17.25s.15-1.93-.08-2.79S1.5,12.9,1.5,12s1.1-1.64,1.32-2.46-.35-2,.08-2.79S4.66,5.9,5.28,5.28,6,3.34,6.75,2.9s1.93.15,2.79-.08S11.1,1.5,12,1.5s1.64,1.1,2.46,1.32,2-.35,2.79.08.85,1.76,1.47,2.38S20.66,6,21.1,6.75s-.15,1.93.08,2.79S22.5,11.1,22.5,12Z"/><line class="cls-2" x1="7.23" y1="16.77" x2="7.23" y2="8.18"/><path class="cls-2" d="M7.16,14.86h1l1.91,1h4.4a1.7,1.7,0,0,0,1.65-1.29l.58-2.33a1.4,1.4,0,0,0,.05-.41h0a1.7,1.7,0,0,0-1.7-1.7H13l.67-1.34a2.65,2.65,0,0,0,.29-1.2h0a1.27,1.27,0,0,0-1.27-1.28h0a1.28,1.28,0,0,0-1,.51L9.14,10.09H7.23"/></svg>
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
    .cls-1,.cls-2{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-1{stroke-linecap:square;}
</style>