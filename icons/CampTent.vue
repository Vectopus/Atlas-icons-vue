
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="22.54 22.56 1.46 22.56 1.46 13.94 12 2.44 22.54 13.94 22.54 22.56"/><line class="cls-1" x1="0.5" y1="22.56" x2="23.5" y2="22.56"/><polyline class="cls-1" points="7.25 22.56 4.33 17.45 12 7.23"/><line class="cls-1" x1="12" y1="7.23" x2="7.25" y2="22.56"/><polyline class="cls-1" points="16.75 22.56 19.67 17.45 12 7.23"/><line class="cls-1" x1="12" y1="7.23" x2="16.75" y2="22.56"/><line class="cls-1" x1="12" y1="2.44" x2="12" y2="7.23"/></svg>
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