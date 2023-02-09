
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M5.32,18.68H18.68a1.91,1.91,0,0,1,1.91,1.91V22.5a0,0,0,0,1,0,0H3.41a0,0,0,0,1,0,0V20.59A1.91,1.91,0,0,1,5.32,18.68Z"/><polygon class="cls-1" points="18.68 3.41 5.32 1.5 5.32 18.68 18.68 18.68 18.68 3.41"/><polygon class="cls-2" points="12 8.18 12.62 9.44 14.01 9.64 13 10.62 13.24 12 12 11.35 10.76 12 11 10.62 9.99 9.64 11.38 9.44 12 8.18"/><line class="cls-1" x1="1.5" y1="22.5" x2="22.5" y2="22.5"/></svg>
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
    .cls-1,.cls-2{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-2{stroke-linecap:square;}
</style>