
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M15.83,7.2h0A3.83,3.83,0,0,0,12,3.37h0A3.83,3.83,0,0,0,8.17,7.2h0a8,8,0,0,1-1.58,4.67,6.7,6.7,0,1,0,10.73-.13A7.47,7.47,0,0,1,15.83,7.2Z"/><circle class="cls-1" cx="12" cy="15.8" r="2.87"/><line class="cls-1" x1="12" y1="0.5" x2="12" y2="3.37"/></svg>
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