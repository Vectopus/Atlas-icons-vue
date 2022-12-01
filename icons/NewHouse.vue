
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="23.5" y1="22.06" x2="0.5" y2="22.06"/><polyline class="cls-1" points="22.54 10.56 12 1.94 1.46 10.56"/><polyline class="cls-1" points="13.92 19.19 10.08 19.19 10.08 13.44 13.92 13.44"/><line class="cls-1" x1="12.96" y1="16.31" x2="10.08" y2="16.31"/><polyline class="cls-1" points="2.42 20.15 2.42 13.44 3.38 13.44 5.29 19.19 6.25 19.19 6.25 12.48"/><polyline class="cls-1" points="22.54 12.48 21.58 19.19 20.63 19.19 19.67 16.31 18.71 19.19 17.75 19.19 16.79 12.48"/></svg>
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