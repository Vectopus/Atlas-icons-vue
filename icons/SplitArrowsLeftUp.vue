
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="15.34" y1="2.5" x2="15.34" y2="23.5"/><polyline class="cls-1" points="20.11 7.27 15.34 2.5 10.57 7.27"/><path class="cls-1" d="M3.89,14H7.7a7.64,7.64,0,0,1,7.64,7.64V23.5"/><polyline class="cls-1" points="8.66 18.73 3.89 13.96 8.66 9.18"/></svg>
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