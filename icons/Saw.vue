
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M2.41,19.65V10.09A5.74,5.74,0,0,1,8.15,4.35h0a5.74,5.74,0,0,1,5.74,5.74v9.56"/><line class="cls-1" x1="0.5" y1="17.74" x2="16.76" y2="17.74"/><path class="cls-1" d="M16.76,15.83h3.83a1.91,1.91,0,0,1,1.91,1.91v0a1.91,1.91,0,0,1-1.91,1.91H16.76a0,0,0,0,1,0,0V15.83A0,0,0,0,1,16.76,15.83Z"/></svg>
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