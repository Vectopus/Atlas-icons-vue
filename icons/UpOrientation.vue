
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><rect class="cls-1" x="6.21" y="13.94" width="11.51" height="5.75"/><rect class="cls-1" x="3.33" y="4.35" width="17.26" height="5.75"/><line class="cls-1" x1="0.45" y1="13.94" x2="23.47" y2="13.94"/><line class="cls-1" x1="0.45" y1="4.35" x2="23.47" y2="4.35"/></g></svg>
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