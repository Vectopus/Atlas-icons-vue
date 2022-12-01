
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><line class="cls-1" x1="0.48" y1="22.57" x2="23.5" y2="22.57"/><rect class="cls-1" x="0.96" y="9.63" width="12.47" height="5.75" transform="translate(-5.31 19.7) rotate(-90)"/><rect class="cls-1" x="8.15" y="7.23" width="17.26" height="5.75" transform="translate(6.68 26.89) rotate(-90)"/></g></svg>
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