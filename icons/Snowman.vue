
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M18.68,15.82A6.68,6.68,0,1,1,8.9,9.9a4.75,4.75,0,0,0,6.2,0A6.67,6.67,0,0,1,18.68,15.82Z"/><path class="cls-1" d="M16.77,6.27A4.79,4.79,0,0,1,15.1,9.9a4.75,4.75,0,0,1-6.2,0,4.77,4.77,0,1,1,7.87-3.63Z"/><line class="cls-1" x1="15.82" y1="13.91" x2="22.5" y2="7.23"/><polyline class="cls-1" points="23.45 10.09 19.64 10.09 19.64 6.27"/><line class="cls-1" x1="8.18" y1="13.91" x2="1.5" y2="7.23"/><polyline class="cls-1" points="0.55 10.09 4.36 10.09 4.36 6.27"/><line class="cls-1" x1="11.05" y1="7.23" x2="12.95" y2="7.23"/><line class="cls-1" x1="11.05" y1="14.86" x2="12.95" y2="14.86"/><line class="cls-1" x1="11.05" y1="18.68" x2="12.95" y2="18.68"/></svg>
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