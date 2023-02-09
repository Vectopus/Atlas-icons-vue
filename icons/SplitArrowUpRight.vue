
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="8.16" y1="2.5" x2="8.16" y2="23.5"/><polyline class="cls-1" points="12.93 7.27 8.16 2.5 3.39 7.27"/><path class="cls-1" d="M19.61,14H15.8a7.64,7.64,0,0,0-7.64,7.64V23.5"/><polyline class="cls-1" points="14.84 18.73 19.61 13.96 14.84 9.18"/></svg>
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