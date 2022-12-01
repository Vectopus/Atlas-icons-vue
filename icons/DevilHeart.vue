
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M16.77,5.3A5.71,5.71,0,0,0,12,7.86,5.73,5.73,0,0,0,1.5,11C1.5,19.61,12,22.48,12,22.48S22.5,19.61,22.5,11A5.72,5.72,0,0,0,16.77,5.3Z"/><path class="cls-1" d="M16.77,9.11A1.91,1.91,0,0,1,18.68,11a6.26,6.26,0,0,1-1.95,4.44"/><path class="cls-2" d="M4.05,7.06C1.2,5,2.59,0,6.27.52A2.46,2.46,0,0,0,4.21,2.81,1.75,1.75,0,0,0,5.54,4.62L4.05,7.06Z"/><path class="cls-2" d="M17.73.52C21.41,0,22.79,5,20,7.06L18.46,4.62a1.75,1.75,0,0,0,1.33-1.81A2.46,2.46,0,0,0,17.73.52Z"/></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-2{fill:currentColor;}
</style>