
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="roll_brush" data-name="roll brush"><path class="cls-1" d="M18.68,12h-1V10.08A5.75,5.75,0,0,0,12,4.33h-.21a5.69,5.69,0,0,0-4.82,3,2.15,2.15,0,0,0-.14.26,6.63,6.63,0,0,0-.56,2.52h0a4.78,4.78,0,0,0-4.8,4.8,1.41,1.41,0,0,0,0,.2,4.8,4.8,0,0,0,4.79,4.59H18.68a3.82,3.82,0,0,0,3.82-3.58,2.17,2.17,0,0,0,0-.26A3.82,3.82,0,0,0,18.68,12Z"/></g></svg>
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