
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="23.5 22.5 1.5 22.5 1.5 0.5"/><polyline class="cls-1" points="1.5 3.37 8.2 10.06 11.06 7.2 22.54 18.67"/><polyline class="cls-1" points="17.76 18.67 22.54 18.67 22.54 13.89"/><line class="cls-1" x1="5.33" y1="14.85" x2="5.33" y2="22.5"/><line class="cls-1" x1="10.11" y1="12.93" x2="10.11" y2="22.5"/><line class="cls-1" x1="14.89" y1="15.8" x2="14.89" y2="22.5"/></svg>
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