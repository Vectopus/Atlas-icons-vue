
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><rect class="cls-1" x="13.92" y="6.26" width="5.75" height="11.51"/><rect class="cls-1" x="4.33" y="3.39" width="5.75" height="17.26"/><line class="cls-1" x1="16.8" y1="6.26" x2="16.8" y2="0.51"/><line class="cls-1" x1="16.8" y1="23.53" x2="16.8" y2="17.77"/><line class="cls-1" x1="7.21" y1="3.39" x2="7.21" y2="0.51"/><line class="cls-1" x1="7.21" y1="23.53" x2="7.21" y2="20.65"/></g></svg>
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