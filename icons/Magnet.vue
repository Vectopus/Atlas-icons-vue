
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M22.5,1.5V12A10.5,10.5,0,0,1,12,22.5h0A10.5,10.5,0,0,1,1.5,12V1.5H7.23V12A4.76,4.76,0,0,0,12,16.77h0A4.76,4.76,0,0,0,16.77,12V1.5Z"/><line class="cls-1" x1="1.5" y1="6.27" x2="7.23" y2="6.27"/><line class="cls-1" x1="16.77" y1="6.27" x2="22.5" y2="6.27"/></svg>
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