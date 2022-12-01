
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M1.46,19.19H4a1.25,1.25,0,0,0,1.25-1.25h0a1.26,1.26,0,0,0-.55-1L3,15.72a1.25,1.25,0,0,1-.55-1h0a1.25,1.25,0,0,1,1.25-1.25H6.25"/><line class="cls-1" x1="23.5" y1="22.06" x2="0.5" y2="22.06"/><polyline class="cls-1" points="22.54 10.56 12 1.94 1.46 10.56"/><rect class="cls-1" x="8.17" y="13.44" width="2.88" height="5.75" rx="1.44"/><polyline class="cls-1" points="13.92 12.48 13.92 19.19 16.79 19.19"/><path class="cls-1" d="M18.71,13.44h1a1.92,1.92,0,0,1,1.92,1.92v1.92a1.92,1.92,0,0,1-1.92,1.92h-1a0,0,0,0,1,0,0V13.44a0,0,0,0,1,0,0Z"/></svg>
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