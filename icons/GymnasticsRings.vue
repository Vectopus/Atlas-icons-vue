
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="6.26" cy="18.67" r="3.83"/><circle class="cls-1" cx="17.74" cy="15.8" r="3.83"/><line class="cls-1" x1="6.26" y1="0.5" x2="6.26" y2="16.76"/><line class="cls-1" x1="17.74" y1="0.5" x2="17.74" y2="13.89"/></svg>
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