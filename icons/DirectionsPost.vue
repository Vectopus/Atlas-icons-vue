
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="18.7 6.28 5.3 6.28 2.44 3.89 5.3 1.5 18.7 1.5 18.7 6.28"/><polygon class="cls-1" points="5.3 10.11 18.7 10.11 21.57 12.5 18.7 14.89 5.3 14.89 5.3 10.11"/><line class="cls-1" x1="12" y1="23.5" x2="12" y2="14.89"/><line class="cls-1" x1="12" y1="10.11" x2="12" y2="6.28"/><line class="cls-1" x1="0.52" y1="22.54" x2="23.48" y2="22.54"/></svg>
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