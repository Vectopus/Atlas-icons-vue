
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M10.09,6.72V1.46H5.3V6.72a6.22,6.22,0,1,0,4.79,0Z"/><line class="cls-1" x1="3.39" y1="1.46" x2="12" y2="1.46"/><line class="cls-1" x1="5.3" y1="5.28" x2="23.48" y2="5.28"/><line class="cls-1" x1="5.3" y1="14.85" x2="23.48" y2="14.85"/><polyline class="cls-1" points="0.52 22.5 20.61 22.5 20.61 0.5"/></svg>
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