
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M9.23,14.83V3.74a1.94,1.94,0,0,1,1.7-2,1.8,1.8,0,0,1,1.49.54A1.83,1.83,0,0,1,13,3.63v6.54l4.92.7a1.87,1.87,0,0,1,1.61,1.84,16.94,16.94,0,0,1-1.78,7.56l-.09.16v2.8"/><path class="cls-1" d="M9.23,23.23v-2.8L6.59,17.79A3.73,3.73,0,0,1,5.5,15.15V10.77A2.46,2.46,0,0,1,6.78,8.55a2.32,2.32,0,0,1,2.45.22"/></svg>
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