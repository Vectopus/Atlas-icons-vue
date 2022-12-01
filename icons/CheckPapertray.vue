
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><polyline class="cls-1" points="8.13 8.15 11.01 11.03 15.81 6.24"/><polygon class="cls-1" points="22.52 14.87 22.52 22.54 1.42 22.54 1.42 14.87 5.26 1.44 18.68 1.44 22.52 14.87"/><path class="cls-1" d="M2.38,14.87H8.13a3.84,3.84,0,0,0,7.68,0h5.75"/><path class="cls-1" d="M22.52,14.87H15.81a3.84,3.84,0,0,1-7.68,0H1.42"/></g></svg>
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