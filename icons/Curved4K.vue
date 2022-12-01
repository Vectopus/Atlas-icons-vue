
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="10.09 8.18 10.09 12.96 6.27 12.96 6.27 12 9.14 8.18 10.09 8.18"/><line class="cls-1" x1="10.09" y1="16.77" x2="10.09" y2="12.95"/><line class="cls-1" x1="13.91" y1="7.23" x2="13.91" y2="16.77"/><path class="cls-1" d="M17.73,7.23V9.14A2.86,2.86,0,0,1,14.86,12h0a2.86,2.86,0,0,1,2.87,2.86v1.91"/><path class="cls-1" d="M22.5,2.45v19.1A31,31,0,0,0,12,19.64,31,31,0,0,0,1.5,21.55V2.45A31,31,0,0,0,12,4.36,31,31,0,0,0,22.5,2.45Z"/></svg>
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