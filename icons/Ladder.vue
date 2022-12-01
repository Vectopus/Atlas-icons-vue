
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="12" y1="19.67" x2="4.39" y2="19.67"/><line class="cls-1" x1="13.29" y1="14.89" x2="5.64" y2="14.89"/><line class="cls-1" x1="14.53" y1="10.11" x2="7.22" y2="10.11"/><line class="cls-1" x1="8.17" y1="5.33" x2="15.83" y2="5.33"/><polyline class="cls-1" points="3.39 23.5 9.13 1.5 16.78 1.5 11.04 23.5"/><line class="cls-1" x1="20.61" y1="23.5" x2="15.83" y2="5.16"/></svg>
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