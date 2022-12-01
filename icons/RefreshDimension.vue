
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="12 16.58 16.89 14.14 16.89 8.77 12 6.36 7.12 8.77 7.12 14.14 12 16.58"/><polyline class="cls-1" points="7.12 8.76 7.13 8.76 12 11.16 12 16.58"/><polyline class="cls-1" points="12 16.58 12 11.16 16.87 8.76 16.88 8.76"/><polyline class="cls-1" points="16.88 8.76 16.87 8.76 12 11.16 7.13 8.76 7.12 8.76"/><path class="cls-1" d="M18.18,3.21A10.75,10.75,0,0,1,12,22.75"/><path class="cls-1" d="M5.82,20.79A10.75,10.75,0,0,1,12,1.25"/><polyline class="cls-1" points="18.84 7.12 17.86 3.21 21.77 3.21"/><polyline class="cls-1" points="5.16 16.89 6.14 20.79 2.23 20.79"/></svg>
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