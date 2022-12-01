
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="15.82 1.5 18.68 1.5 22.5 14.86 22.5 22.5 1.5 22.5 1.5 14.86 5.32 1.5 8.18 1.5 15.82 1.5"/><circle class="cls-2" cx="18.68" cy="18.68" r="0.95"/><line class="cls-1" x1="12" y1="18.68" x2="15.82" y2="18.68"/><line class="cls-1" x1="1.5" y1="14.86" x2="22.5" y2="14.86"/></svg>
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