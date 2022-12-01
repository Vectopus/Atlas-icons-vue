
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><rect class="cls-1" x="8.13" y="-5.23" width="7.67" height="21.1" transform="translate(17.29 -6.65) rotate(90)"/><rect class="cls-1" x="13.89" y="7.24" width="6.71" height="10.55" transform="translate(4.73 29.76) rotate(-90)"/><rect class="cls-1" x="3.34" y="7.24" width="6.71" height="10.55" transform="translate(-5.82 19.21) rotate(-90)"/><rect class="cls-1" x="13.89" y="13.95" width="6.71" height="10.55" transform="translate(-1.98 36.47) rotate(-90)"/><rect class="cls-1" x="3.34" y="13.95" width="6.71" height="10.55" transform="translate(-12.53 25.92) rotate(-90)"/></g></svg>
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