
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="6.26" cy="4.37" r="2.87"/><path class="cls-1" d="M11,13.93h0A4.78,4.78,0,0,0,6.26,9.15h0a4.78,4.78,0,0,0-4.78,4.78h0"/><circle class="cls-1" cx="17.74" cy="13.93" r="2.87"/><path class="cls-1" d="M22.52,23.5h0a4.78,4.78,0,0,0-4.78-4.78h0A4.78,4.78,0,0,0,13,23.5h0"/><line class="cls-1" x1="12" y1="5.33" x2="20.61" y2="5.33"/><polyline class="cls-1" points="17.74 2.46 20.61 5.33 17.74 8.2"/><line class="cls-1" x1="12" y1="18.72" x2="3.39" y2="18.72"/><polyline class="cls-1" points="6.26 15.85 3.39 18.72 6.26 21.59"/></svg>
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