
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><rect class="cls-1" x="6.25" y="13.94" width="11.51" height="5.75"/><rect class="cls-1" x="3.38" y="4.34" width="17.26" height="5.75"/><line class="cls-1" x1="23.52" y1="16.81" x2="17.76" y2="16.81"/><line class="cls-1" x1="6.25" y1="16.81" x2="0.5" y2="16.81"/><line class="cls-1" x1="23.52" y1="7.22" x2="20.64" y2="7.22"/><line class="cls-1" x1="3.38" y1="7.22" x2="0.5" y2="7.22"/></g></svg>
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