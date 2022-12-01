
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><polyline class="cls-1" points="23.47 17.77 6.2 17.77 6.2 0.51"/><line class="cls-1" x1="17.71" y1="23.53" x2="17.71" y2="20.65"/><polyline class="cls-1" points="9.08 6.26 17.71 6.26 17.71 17.77"/><line class="cls-1" x1="6.2" y1="6.26" x2="0.45" y2="6.26"/></g></svg>
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