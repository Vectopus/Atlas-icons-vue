
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="14.88 17.77 9.13 17.77 7.21 13.94 16.79 13.94 14.88 17.77"/><line class="cls-1" x1="12" y1="23.52" x2="12" y2="17.77"/><path class="cls-1" d="M15.45,13.94a6.71,6.71,0,1,0-6.9,0"/><line class="cls-1" x1="0.5" y1="22.56" x2="23.5" y2="22.56"/><circle class="cls-2" cx="12" cy="11.06"/><circle class="cls-2" cx="14.88" cy="8.19"/><circle class="cls-2" cx="14.88" cy="11.06"/></svg>
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
    .cls-1,.cls-2{fill:none;stroke:currentColor;}.cls-1{stroke-miterlimit:10;}.cls-2{stroke-linecap:round;stroke-linejoin:round;}
</style>