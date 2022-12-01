
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><rect class="cls-1" x="1.46" y="1.5" width="21.1" height="21.1"/><polygon class="cls-1" points="22.56 7.25 16.28 7.25 14.37 7.25 1.46 7.25 1.46 1.5 22.56 1.5 22.56 7.25"/><line class="cls-1" x1="4.34" y1="4.38" x2="6.25" y2="4.38"/><line class="cls-1" x1="8.17" y1="4.38" x2="10.09" y2="4.38"/><line class="cls-1" x1="12.01" y1="4.38" x2="13.93" y2="4.38"/></g></svg>
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