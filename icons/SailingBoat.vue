
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M1.5,17.7h21a0,0,0,0,1,0,0v0a4.77,4.77,0,0,1-4.77,4.77H6.27A4.77,4.77,0,0,1,1.5,17.7v0A0,0,0,0,1,1.5,17.7Z"/><path class="cls-1" d="M20.59,13.89H12V2.43h0a11,11,0,0,1,8.59,10.71Z"/><polygon class="cls-1" points="12 13.89 4.36 13.89 12 5.29 12 13.89"/><line class="cls-1" x1="12" y1="0.52" x2="12" y2="17.7"/><rect class="cls-1" x="7.23" y="1.48" width="4.77" height="3.82"/></svg>
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