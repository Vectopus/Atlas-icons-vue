
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M19.67,21.59H4.37A2.87,2.87,0,0,1,1.5,18.72V3.41H9.15L12,7.24H22.54V18.72A2.87,2.87,0,0,1,19.67,21.59Z"/><line class="cls-1" x1="12.02" y1="3.41" x2="23.5" y2="3.41"/></svg>
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