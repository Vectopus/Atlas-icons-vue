
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><polyline class="cls-1" points="8.14 17.8 5.26 14.92 8.14 12.04"/><polyline class="cls-1" points="15.81 17.8 18.69 14.92 15.81 12.04"/><line class="cls-1" x1="10.06" y1="17.8" x2="13.89" y2="12.04"/><rect class="cls-1" x="1.43" y="1.49" width="21.1" height="21.1"/><polygon class="cls-1" points="22.53 7.25 16.25 7.25 14.33 7.25 1.43 7.25 1.43 1.49 22.53 1.49 22.53 7.25"/><line class="cls-1" x1="4.3" y1="4.37" x2="6.22" y2="4.37"/><line class="cls-1" x1="8.14" y1="4.37" x2="10.06" y2="4.37"/><line class="cls-1" x1="11.98" y1="4.37" x2="13.89" y2="4.37"/></g></svg>
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