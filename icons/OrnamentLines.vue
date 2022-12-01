
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="14.85" r="7.65"/><polyline class="cls-1" points="8.17 8.23 8.17 3.37 15.83 3.37 15.83 8.23"/><line class="cls-1" x1="12" y1="0.5" x2="12" y2="3.37"/><polyline class="cls-1" points="4.79 12.3 6.89 13.89 9.45 11.98 11.99 13.89 14.54 11.98 17.1 13.89 19.21 12.3"/><polyline class="cls-1" points="4.65 16.99 6.89 18.67 9.45 16.76 11.99 18.67 14.54 16.76 17.1 18.67 19.35 16.99"/></svg>
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