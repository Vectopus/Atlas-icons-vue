
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><polyline class="cls-1" points="6.25 15.83 1.46 15.83 1.46 1.45 15.85 1.45 15.85 6.24"/><polyline class="cls-1" points="17.76 8.16 22.56 8.16 22.56 22.55 8.17 22.55 8.17 17.75"/><line class="cls-1" x1="7.21" y1="12" x2="9.13" y2="12"/><line class="cls-1" x1="7.21" y1="8.16" x2="9.13" y2="8.16"/><line class="cls-1" x1="11.05" y1="8.16" x2="12.97" y2="8.16"/><line class="cls-1" x1="11.05" y1="15.83" x2="12.97" y2="15.83"/><line class="cls-1" x1="14.89" y1="15.83" x2="16.8" y2="15.83"/><line class="cls-1" x1="14.89" y1="12" x2="16.8" y2="12"/><line class="cls-1" x1="14.89" y1="8.16" x2="16.8" y2="8.16"/><line class="cls-1" x1="7.21" y1="15.83" x2="9.13" y2="15.83"/></g></svg>
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