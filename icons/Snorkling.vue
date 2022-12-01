
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M20.59,14.84H15.82l-.53-1.05a1.54,1.54,0,0,0-1.38-.86h0a1.53,1.53,0,0,0-1.38.86L12,14.84H7.23a1.9,1.9,0,0,1-1.91-1.91V6.25A1.91,1.91,0,0,1,7.23,4.34H20.59A1.91,1.91,0,0,1,22.5,6.25v6.68A1.9,1.9,0,0,1,20.59,14.84Z"/><line class="cls-1" x1="12" y1="18.66" x2="15.82" y2="18.66"/><path class="cls-1" d="M13.91,18.66h0a3.82,3.82,0,0,1-3.82,3.82H5.32A3.82,3.82,0,0,1,1.5,18.66V.52"/></svg>
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