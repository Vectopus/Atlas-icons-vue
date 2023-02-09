
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="6.28 15.85 2.46 12.02 6.28 8.2"/><path class="cls-1" d="M2.46,12H17.28a5.25,5.25,0,0,0,5.26-5.26h0A5.26,5.26,0,0,0,17.28,1.5h0A5.27,5.27,0,0,0,12,6.76v3.35"/><line class="cls-1" x1="12.02" y1="13.93" x2="12.02" y2="23.5"/></svg>
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