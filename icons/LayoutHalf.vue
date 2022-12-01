
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><rect class="cls-1" x="1.45" y="1.49" width="8.63" height="21.1"/><rect class="cls-1" x="10.08" y="1.49" width="12.47" height="10.55" transform="translate(32.64 13.52) rotate(180)"/><rect class="cls-1" x="10.08" y="12.04" width="12.47" height="10.55" transform="translate(32.64 34.62) rotate(180)"/></g></svg>
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