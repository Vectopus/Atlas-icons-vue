
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M16,17.56A8,8,0,0,1,14.77,2,10.05,10.05,0,0,0,12,1.63a10.37,10.37,0,0,0,0,20.74,10.15,10.15,0,0,0,4.67-1.12"/><path class="cls-1" d="M22.64,18.94a3.43,3.43,0,1,1-6.86,0c0-3.43,3.43-6,3.43-6S22.64,15.51,22.64,18.94Z"/></svg>
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