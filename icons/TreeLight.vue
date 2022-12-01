
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M17.74,12.93c0,4.23-2.57,9.57-5.74,9.57s-5.74-5.34-5.74-9.57S8.83,7.2,12,7.2,17.74,8.71,17.74,12.93Z"/><polyline class="cls-1" points="8.17 8.23 8.17 3.37 15.83 3.37 15.83 8.23"/><line class="cls-1" x1="12" y1="0.5" x2="12" y2="3.37"/><line class="cls-1" x1="16.22" y1="18.99" x2="7.04" y2="17.27"/><line class="cls-1" x1="17.48" y1="15.39" x2="6.27" y2="13.3"/><line class="cls-1" x1="17.64" y1="11.61" x2="7.03" y2="9.61"/></svg>
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