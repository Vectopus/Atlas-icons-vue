
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="Pound"><path class="cls-1" d="M18.68,7.23v-1A4.78,4.78,0,0,0,13.91,1.5h0A4.77,4.77,0,0,0,9.14,6.27V16.65A4.77,4.77,0,0,1,7.78,20L5.32,22.5H18.68"/><line class="cls-1" x1="5.32" y1="12" x2="12.95" y2="12"/></g></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-linecap:square;stroke-miterlimit:10;}
</style>