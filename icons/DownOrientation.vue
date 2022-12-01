
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><rect class="cls-1" x="6.22" y="4.35" width="11.51" height="5.75"/><rect class="cls-1" x="3.34" y="13.94" width="17.26" height="5.75"/><line class="cls-1" x1="23.48" y1="10.11" x2="0.46" y2="10.11"/><line class="cls-1" x1="23.48" y1="19.7" x2="0.46" y2="19.7"/></g></svg>
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