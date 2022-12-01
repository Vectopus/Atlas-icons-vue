
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="1.46 19.67 12 4.33 22.54 19.67"/><line class="cls-1" x1="23.5" y1="19.67" x2="0.5" y2="19.67"/><polyline class="cls-1" points="14.4 7.82 12 11.3 9.6 14.79 7.21 18.28 6.25 19.67"/><polyline class="cls-1" points="16.79 11.3 14.4 14.79 12 18.28 11.04 19.67"/><polyline class="cls-1" points="19.19 14.79 16.79 18.28 15.83 19.67"/><polyline class="cls-1" points="9.6 7.82 12 11.3 14.4 14.79 16.79 18.28 17.75 19.67"/><polyline class="cls-1" points="7.21 11.3 9.6 14.79 12 18.28 12.96 19.67"/><polyline class="cls-1" points="4.81 14.79 7.21 18.28 8.17 19.67"/></svg>
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