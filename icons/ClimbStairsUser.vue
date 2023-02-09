
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="0.5 22.54 9.13 22.54 9.13 17.75 16.79 17.75 16.79 12 23.5 12"/><polyline class="cls-1" points="4.33 20.63 4.33 12.92 4.33 11.04 4.33 7.21 8.17 7.21 8.17 12 11.04 12 11.04 15.83"/><line class="cls-1" x1="13.92" y1="7.21" x2="8.17" y2="7.21"/><circle class="cls-1" cx="6.25" cy="3.38" r="1.92"/></svg>
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