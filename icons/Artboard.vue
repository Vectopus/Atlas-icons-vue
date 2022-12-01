
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><rect class="cls-1" x="1.45" y="1.46" width="3.84" height="3.84"/><rect class="cls-1" x="18.71" y="1.46" width="3.84" height="3.84"/><rect class="cls-1" x="1.45" y="18.72" width="3.84" height="3.84"/><rect class="cls-1" x="18.71" y="18.72" width="3.84" height="3.84"/><line class="cls-1" x1="18.71" y1="3.38" x2="5.28" y2="3.38"/><line class="cls-1" x1="18.71" y1="20.64" x2="5.28" y2="20.64"/><line class="cls-1" x1="3.36" y1="18.72" x2="3.36" y2="5.3"/><line class="cls-1" x1="20.63" y1="18.72" x2="20.63" y2="5.3"/></g></svg>
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