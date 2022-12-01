
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="2.45" r="0.95"/><circle class="cls-1" cx="12" cy="15.82" r="0.95"/><circle class="cls-1" cx="12" cy="9.14" r="0.95"/><circle class="cls-1" cx="6.21" cy="5.8" r="0.95"/><circle class="cls-1" cx="17.79" cy="12.48" r="0.95"/><circle class="cls-1" cx="17.79" cy="5.8" r="0.95"/><circle class="cls-1" cx="6.21" cy="12.48" r="0.95"/><circle class="cls-1" cx="12" cy="9.14" r="6.68"/><line class="cls-1" x1="0.55" y1="22.5" x2="23.45" y2="22.5"/><polyline class="cls-1" points="14.24 15.43 16.77 22.5 7.23 22.5 9.76 15.43"/></svg>
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