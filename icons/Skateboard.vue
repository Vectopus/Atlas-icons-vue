
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="17.73" y1="12.95" x2="12.95" y2="17.73"/><line class="cls-1" x1="11.05" y1="6.27" x2="6.27" y2="11.05"/><path class="cls-1" d="M13.91,3.41l.52-.53a4.73,4.73,0,0,1,6.69,6.69l-.53.52"/><path class="cls-1" d="M3.41,13.91l-.53.52a4.73,4.73,0,0,0,6.69,6.69l.52-.53"/><rect class="cls-1" x="11.13" y="2.82" width="2.7" height="4.05" transform="translate(7.08 -7.4) rotate(45)"/><rect class="cls-1" x="17.81" y="9.5" width="2.7" height="4.05" transform="translate(13.76 -10.17) rotate(45)"/><line class="cls-1" x1="18.2" y1="10.57" x2="13.43" y2="5.8"/><rect class="cls-1" x="3.49" y="10.45" width="2.7" height="4.05" transform="translate(10.24 0.23) rotate(45)"/><rect class="cls-1" x="10.17" y="17.13" width="2.7" height="4.05" transform="translate(16.92 -2.54) rotate(45)"/><line class="cls-1" x1="10.57" y1="18.2" x2="5.8" y2="13.43"/></svg>
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