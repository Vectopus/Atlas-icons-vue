
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="22.54 17.75 12 6.25 2.42 17.75"/><line class="cls-1" x1="12" y1="6.25" x2="16.79" y2="17.75"/><line class="cls-1" x1="10.08" y1="14.88" x2="10.08" y2="17.75"/><line class="cls-1" x1="0.5" y1="17.75" x2="23.5" y2="17.75"/></svg>
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