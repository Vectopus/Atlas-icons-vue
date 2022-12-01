
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><polygon class="cls-1" points="21.54 8.18 11.95 13.93 2.36 8.18 11.95 2.42 21.54 8.18"/><polyline class="cls-1" points="18.35 13.93 21.54 15.85 11.95 21.6 2.36 15.85 5.55 13.93"/><polyline class="cls-1" points="5.55 10.09 2.36 12.01 5.55 13.93 11.95 17.77 18.35 13.93 21.54 12.01 18.35 10.09"/></g></svg>
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