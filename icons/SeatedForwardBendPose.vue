
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M22.5,13.91v3.82H4A2.49,2.49,0,0,1,1.5,15.24h0a2.5,2.5,0,0,1,1.11-2.07l1.44-1a12.63,12.63,0,0,1,7-2.12H13l1.91,4.77h5.73"/><path class="cls-1" d="M2.86,17.46,5,16a12.55,12.55,0,0,1,7-2.12"/><circle class="cls-1" cx="18.2" cy="8.66" r="2.39"/></svg>
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