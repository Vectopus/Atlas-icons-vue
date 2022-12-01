
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="19.64 22.5 4.36 22.5 2.46 9.14 21.55 9.14 19.64 22.5"/><ellipse class="cls-1" cx="12" cy="15.82" rx="4.77" ry="3.82"/><circle class="cls-2" cx="12" cy="15.82" r="0.95"/><line class="cls-1" x1="3.41" y1="5.32" x2="20.59" y2="5.32"/><line class="cls-1" x1="5.32" y1="1.5" x2="18.68" y2="1.5"/></svg>
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