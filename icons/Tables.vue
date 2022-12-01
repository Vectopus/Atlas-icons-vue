
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><polygon class="cls-1" points="15.83 1.46 6.24 1.46 1.45 1.46 1.45 8.17 6.24 8.17 15.83 8.17 22.55 8.17 22.55 1.46 15.83 1.46"/><rect class="cls-1" x="15.83" y="8.17" width="6.71" height="4.8"/><rect class="cls-1" x="1.45" y="8.17" width="6.71" height="4.8"/><rect class="cls-1" x="8.16" y="8.17" width="7.67" height="4.8"/><rect class="cls-1" x="15.83" y="12.96" width="6.71" height="4.8"/><rect class="cls-1" x="1.45" y="12.96" width="6.71" height="4.8"/><rect class="cls-1" x="8.16" y="12.96" width="7.67" height="4.8"/><rect class="cls-1" x="15.83" y="17.76" width="6.71" height="4.8"/><rect class="cls-1" x="1.45" y="17.76" width="6.71" height="4.8"/><rect class="cls-1" x="8.16" y="17.76" width="7.67" height="4.8"/></g></svg>
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