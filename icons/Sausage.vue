
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M16.6,16.6a26.18,26.18,0,0,1-8.77,5.64A3.6,3.6,0,0,1,3,19.6H3a3.6,3.6,0,0,1,2.18-4,19.07,19.07,0,0,0,6.38-4.05,19.07,19.07,0,0,0,4.05-6.38A3.6,3.6,0,0,1,19.6,3h0a3.6,3.6,0,0,1,2.64,4.87A26.18,26.18,0,0,1,16.6,16.6Z"/><path class="cls-1" d="M3.15,20.22a21,21,0,0,1-2.65.62"/><path class="cls-1" d="M20.84.5a21,21,0,0,1-.62,2.65"/><line class="cls-1" x1="14.06" y1="14.06" x2="11.52" y2="11.52"/><line class="cls-1" x1="17.45" y1="8.98" x2="14.91" y2="8.13"/><line class="cls-1" x1="8.98" y1="17.45" x2="8.13" y2="14.91"/></svg>
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