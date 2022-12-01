
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="22.5 15.84 22.5 22.52 1.5 22.52 1.5 15.84"/><line class="cls-1" x1="12" y1="3.43" x2="12" y2="19.66"/><polyline class="cls-1" points="5.32 9.16 12 2.48 18.68 9.16"/></svg>
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