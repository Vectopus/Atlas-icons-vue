
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="22.5 15.79 22.5 22.48 1.5 22.48 1.5 15.79"/><line class="cls-1" x1="12" y1="16.75" x2="12" y2="0.52"/><polyline class="cls-1" points="18.68 11.02 12 17.7 5.32 11.02"/></svg>
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