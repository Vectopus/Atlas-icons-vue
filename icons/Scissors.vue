
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="19.64" cy="19.64" r="2.86"/><circle class="cls-1" cx="4.36" cy="19.64" r="2.86"/><line class="cls-1" x1="7.28" y1="19.72" x2="18.96" y2="1.22"/><line class="cls-1" x1="16.77" y1="19.88" x2="5.31" y2="0.79"/></svg>
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