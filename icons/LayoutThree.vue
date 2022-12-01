
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><rect class="cls-1" x="1.46" y="1.49" width="21.1" height="6.71"/><rect class="cls-1" x="1.46" y="8.2" width="6.71" height="14.39"/><rect class="cls-1" x="15.84" y="8.2" width="6.71" height="14.39"/><rect class="cls-1" x="8.17" y="8.2" width="7.67" height="14.39"/></g></svg>
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