
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><path class="cls-1" d="M12,22.54V16.79h6.71a3.83,3.83,0,0,0,2.72-1.13,3.9,3.9,0,0,0,1.11-2.45V13a3.84,3.84,0,0,0-3.84-3.84h-1V7.2a5.69,5.69,0,0,0-1.69-4.07A5.66,5.66,0,0,0,12,1.44H11.8A5.75,5.75,0,0,0,7,4.41l-.13.26A6.5,6.5,0,0,0,6.27,7.2h0A4.78,4.78,0,0,0,1.46,12a1.27,1.27,0,0,0,0,.2,4.79,4.79,0,0,0,4.78,4.6H9.13"/><polyline class="cls-1" points="9.13 19.66 12.01 22.54 14.89 19.66"/></g></svg>
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