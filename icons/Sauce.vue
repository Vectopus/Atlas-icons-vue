
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M16.22,5.44h0a13.1,13.1,0,0,1-4.87.94h-5v4.68a4.68,4.68,0,0,0,4.68,4.69h2.82a4.69,4.69,0,0,0,4.68-4.69h0l3.75-5.62V4.5H21.09A13.1,13.1,0,0,0,16.22,5.44Z"/><circle class="cls-1" cx="4.03" cy="6.84" r="2.34"/><polygon class="cls-1" points="9.19 15.75 15.75 15.75 17.63 19.5 7.31 19.5 9.19 15.75"/></svg>
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