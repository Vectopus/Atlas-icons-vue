
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M5.32,1.5H18.68a0,0,0,0,1,0,0V8.18A6.68,6.68,0,0,1,12,14.86h0A6.68,6.68,0,0,1,5.32,8.18V1.5a0,0,0,0,1,0,0Z"/><line class="cls-1" x1="12" y1="22.5" x2="12" y2="14.86"/><line class="cls-1" x1="16.77" y1="22.5" x2="7.23" y2="22.5"/><path class="cls-1" d="M5.32,7.23C12,4.36,12,10.09,18.68,7.23"/></svg>
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