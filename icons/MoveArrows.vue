
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="8.95 5.28 12 2.23 15.05 5.28"/><polyline class="cls-1" points="15.05 18.72 12 21.77 8.95 18.72"/><polyline class="cls-1" points="5.28 15.05 2.23 12 5.28 8.95"/><polyline class="cls-1" points="18.72 8.95 21.77 12 18.72 15.05"/><line class="cls-1" x1="12" y1="21.77" x2="12" y2="13.95"/><line class="cls-1" x1="12" y1="10.05" x2="12" y2="2.23"/><line class="cls-1" x1="21.77" y1="12" x2="13.95" y2="12"/><line class="cls-1" x1="10.05" y1="12" x2="2.23" y2="12"/><circle class="cls-1" cx="12" cy="12" r="1.95"/></svg>
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