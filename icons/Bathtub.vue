
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M2.42,13.94H21.58a0,0,0,0,1,0,0v1a5.75,5.75,0,0,1-5.75,5.75H8.17A5.75,5.75,0,0,1,2.42,14.9v-1A0,0,0,0,1,2.42,13.94Z"/><polyline class="cls-1" points="4.33 23.52 4.33 22.56 6.25 20.65"/><polyline class="cls-1" points="19.67 23.52 19.67 22.56 17.75 20.65"/><path class="cls-1" d="M2.42,13.94V3.87A2.39,2.39,0,0,1,4.81,1.48h0a2.39,2.39,0,0,1,2.4,2.39V5.31"/><line class="cls-1" x1="5.29" y1="5.31" x2="9.13" y2="5.31"/><line class="cls-1" x1="0.5" y1="13.94" x2="23.5" y2="13.94"/></svg>
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