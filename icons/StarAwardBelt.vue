
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="12" r="6"/><polygon class="cls-1" points="12 10 12.65 11.32 14.1 11.53 13.05 12.55 13.3 14 12 13.32 10.7 14 10.95 12.55 9.9 11.53 11.35 11.32 12 10"/><polyline class="cls-2" points="17.19 9 22 9 21 12 22 15 17.19 15"/><polyline class="cls-2" points="6.81 15 2 15 3 12 2 9 6.81 9"/></svg>
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
    .cls-1,.cls-2{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-1{stroke-linecap:square;}
</style>