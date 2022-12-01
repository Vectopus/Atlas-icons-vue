
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M1.5,5.32H7.23a0,0,0,0,1,0,0V8.18a1.91,1.91,0,0,1-1.91,1.91H3.41A1.91,1.91,0,0,1,1.5,8.18V5.32a0,0,0,0,1,0,0Z"/><rect class="cls-1" x="2.45" y="1.5" width="3.82" height="3.82"/><path class="cls-1" d="M16.77,15.82H22.5a0,0,0,0,1,0,0v4.77a1.91,1.91,0,0,1-1.91,1.91H18.68a1.91,1.91,0,0,1-1.91-1.91V15.82a0,0,0,0,1,0,0Z" transform="translate(39.27 38.32) rotate(180)"/><path class="cls-1" d="M4.36,10.09v8.59A3.82,3.82,0,0,0,8.18,22.5h0A3.82,3.82,0,0,0,12,18.68V5.32A3.82,3.82,0,0,1,15.82,1.5h0a3.82,3.82,0,0,1,3.82,3.82v10.5"/></svg>
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