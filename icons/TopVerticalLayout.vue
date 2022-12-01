
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><rect class="cls-1" x="7.66" y="-4.75" width="8.63" height="21.1" transform="translate(17.78 -6.17) rotate(90)"/><rect class="cls-1" x="11.02" y="11.08" width="12.47" height="10.55" transform="translate(0.9 33.6) rotate(-90)"/><rect class="cls-1" x="0.47" y="11.08" width="12.47" height="10.55" transform="translate(-9.65 23.05) rotate(-90)"/></g></svg>
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