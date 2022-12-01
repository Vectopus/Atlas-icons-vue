
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="14.39" cy="10.52" r="1.43"/><path class="cls-2" d="M22.5,10.05v10.5l-2.86-2.87H11.05a3.81,3.81,0,0,1-3.7-2.86,3.77,3.77,0,0,1-.12-1V10.05a3.82,3.82,0,0,1,3.82-3.82h7.63A3.82,3.82,0,0,1,22.5,10.05Z"/><path class="cls-2" d="M16.77,5.27v1H11.05a3.82,3.82,0,0,0-3.82,3.82v2.86H4.36L1.5,15.77V5.27A3.82,3.82,0,0,1,5.32,1.45H13A3.82,3.82,0,0,1,16.77,5.27Z"/><path class="cls-1" d="M14.39,12h0a2.39,2.39,0,0,1,2.39,2.39v.48a0,0,0,0,1,0,0H12a0,0,0,0,1,0,0v-.48A2.39,2.39,0,0,1,14.39,12Z"/></svg>
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
    .cls-1{fill:currentColor;}.cls-2{fill:none;stroke:currentColor;stroke-miterlimit:10;}
</style>