
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M1.5,11c6.68-6.78,14.32,3.57,21-.95"/><path class="cls-1" d="M1.5,14.86c6.68-6.78,14.32,3.57,21-1"/><path class="cls-1" d="M22.5,17.72C17,21.45,10.82,15.06,5.08,16.52A2.81,2.81,0,0,1,1.5,13.85V7.22c5.68-5.76,12,.84,17.92.19a2.78,2.78,0,0,1,3.08,2.76Z"/></svg>
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