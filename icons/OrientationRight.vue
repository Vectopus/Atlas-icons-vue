
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><line class="cls-1" x1="22.55" y1="0.52" x2="22.55" y2="23.53"/><rect class="cls-1" x="6.25" y="4.35" width="12.47" height="5.75" transform="translate(24.96 14.46) rotate(180)"/><rect class="cls-1" x="1.45" y="13.94" width="17.26" height="5.75" transform="translate(20.17 33.64) rotate(180)"/></g></svg>
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