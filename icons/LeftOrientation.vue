
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><rect class="cls-1" x="13.88" y="6.27" width="5.75" height="11.51"/><rect class="cls-1" x="4.28" y="3.39" width="5.75" height="17.26"/><line class="cls-1" x1="13.88" y1="23.53" x2="13.88" y2="0.52"/><line class="cls-1" x1="4.28" y1="23.53" x2="4.28" y2="0.52"/></g></svg>
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