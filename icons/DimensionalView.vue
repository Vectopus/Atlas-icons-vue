
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="12 18.63 18.84 15.21 18.84 7.68 12 4.32 5.16 7.68 5.16 15.21 12 18.63"/><polyline class="cls-1" points="5.16 8.09 5.19 8.09 12 11.46 12 18.84"/><polyline class="cls-1" points="12 18.84 12 11.46 18.81 8.09 18.84 8.09"/><polyline class="cls-1" points="18.84 8.09 18.81 8.09 12 11.46 5.19 8.09 5.16 8.09"/><polyline class="cls-1" points="1.25 6.14 1.25 1.25 6.14 1.25"/><polyline class="cls-1" points="6.14 22.75 1.25 22.75 1.25 17.86"/><polyline class="cls-1" points="22.75 17.86 22.75 22.75 17.86 22.75"/><polyline class="cls-1" points="17.86 1.25 22.75 1.25 22.75 6.14"/></svg>
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