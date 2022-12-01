
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M21.51,7.25,8,20.78,2.5,21.5,3.22,16,16.75,2.49a3.34,3.34,0,0,1,2.38-1h0A3.37,3.37,0,0,1,22.5,4.87h0A3.34,3.34,0,0,1,21.51,7.25Z"/><line class="cls-1" x1="14.88" y1="4.36" x2="19.64" y2="9.12"/><path class="cls-1" d="M8,20.77H8L2.5,21.5,3.22,16h0a6.59,6.59,0,0,1,3,1.74A6.59,6.59,0,0,1,8,20.77Z"/><line class="cls-1" x1="17.26" y1="6.74" x2="6.26" y2="17.74"/></svg>
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