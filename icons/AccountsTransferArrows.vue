
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="6.27" cy="4.39" r="2.86"/><path class="cls-1" d="M11.05,13.93h0A4.78,4.78,0,0,0,6.27,9.16h0A4.78,4.78,0,0,0,1.5,13.93h0"/><circle class="cls-1" cx="17.73" cy="13.93" r="2.86"/><path class="cls-1" d="M22.5,23.48h0a4.78,4.78,0,0,0-4.77-4.78h0A4.78,4.78,0,0,0,13,23.48h0"/><line class="cls-1" x1="21.55" y1="5.34" x2="12.95" y2="5.34"/><polyline class="cls-1" points="15.82 2.48 12.96 5.34 15.82 8.21"/><line class="cls-1" x1="2.45" y1="18.7" x2="11.05" y2="18.7"/><polyline class="cls-1" points="8.18 15.84 11.04 18.7 8.18 21.57"/></svg>
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