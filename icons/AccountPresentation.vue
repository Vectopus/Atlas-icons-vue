
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="4.33" cy="6.75" r="2.4"/><polyline class="cls-1" points="6.25 23.52 6.25 17.77 7.21 16.81 7.21 11.06 1.46 11.06 1.46 16.81 2.42 17.77 2.42 23.52"/><line class="cls-1" x1="0.5" y1="1.48" x2="23.5" y2="1.48"/><polyline class="cls-1" points="9.13 16.81 21.58 16.81 21.58 1.48 9.13 1.48"/><polyline class="cls-1" points="10.08 11.06 12.96 8.19 14.88 10.1 17.75 7.23"/></svg>
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