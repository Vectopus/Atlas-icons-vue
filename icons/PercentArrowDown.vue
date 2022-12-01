
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="3 13.5 12 22.5 21 13.5 18 13.5 18 1.5 6 1.5 6 13.5 3 13.5"/><circle class="cls-2" cx="10" cy="6.5" r="1"/><circle class="cls-2" cx="14" cy="10.5" r="1"/><line class="cls-1" x1="14" y1="5.5" x2="10" y2="11.5"/></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-2{fill:currentColor;}
</style>