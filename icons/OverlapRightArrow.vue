
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="17.72 15.85 21.54 12.02 17.72 8.2"/><path class="cls-1" d="M21.54,12H6.72A5.25,5.25,0,0,1,1.46,6.76h0A5.26,5.26,0,0,1,6.72,1.5h0A5.27,5.27,0,0,1,12,6.76v3.35"/><line class="cls-1" x1="11.98" y1="13.93" x2="11.98" y2="23.5"/></svg>
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