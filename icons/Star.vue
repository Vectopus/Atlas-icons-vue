
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="12 2.78 14.94 8.73 21.5 9.68 16.75 14.31 17.87 20.85 12 17.77 6.13 20.85 7.25 14.31 2.5 9.68 9.06 8.73 12 2.78"/><polyline class="cls-1" points="7.25 11.04 13.9 11.04 10.1 14.84 19.6 14.84"/></svg>
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