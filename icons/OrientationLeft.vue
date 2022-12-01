
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><line class="cls-1" x1="1.46" y1="0.52" x2="1.46" y2="23.53"/><rect class="cls-1" x="5.3" y="4.35" width="12.47" height="5.75"/><rect class="cls-1" x="5.3" y="13.94" width="17.26" height="5.75"/></g></svg>
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