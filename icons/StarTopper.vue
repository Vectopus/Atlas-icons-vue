
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="12 1.72 14.53 5.8 19.19 6.94 16.09 10.61 16.44 15.4 12 13.58 7.56 15.4 7.92 10.61 4.81 6.94 9.47 5.8 12 1.72"/><polyline class="cls-1" points="13.53 14.21 15 22.28 9 22.28 10.47 14.21"/></svg>
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