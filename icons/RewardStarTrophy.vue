
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="12 2.5 13.5 5.63 16.86 6.14 14.43 8.58 15 12.02 12 10.4 9 12.02 9.57 8.58 7.14 6.14 10.5 5.63 12 2.5"/><line class="cls-1" x1="6.29" y1="22.5" x2="17.71" y2="22.5"/><polygon class="cls-2" points="15.81 22.5 8.19 22.5 12 11.07 15.81 22.5"/></svg>
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
    .cls-1,.cls-2{fill:none;stroke:currentColor;}.cls-1{stroke-miterlimit:10;}.cls-2{stroke-linejoin:bevel;}
</style>