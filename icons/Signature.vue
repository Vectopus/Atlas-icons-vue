
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="16.75 20.59 16.75 22.5 1.48 22.5 1.48 1.5 16.75 1.5 16.75 12.96"/><path class="cls-2" d="M13.89,7.23h0Z"/><path class="cls-2" d="M13.89,11.05h0Z"/><polyline class="cls-1" points="5.29 19.64 5.29 18.68 7.21 15.82 8.16 18.68 10.07 17.73 11.02 18.68 13.89 18.68"/><polygon class="cls-1" points="16.75 18.68 15.79 18.68 15.79 17.73 20.57 12.96 21.52 13.91 16.75 18.68"/></svg>
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
    .cls-1,.cls-2{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-2{stroke-linecap:square;}
</style>