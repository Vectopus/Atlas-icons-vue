
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M6.81,15.78,3.5,17.67,12,22.39l8.5-4.72V6.33L12,1.61,3.5,6.33V9.17L12,13.89l4.72-2.63V16L12,18.61ZM12,9.17,8.69,7.28,12,5.39l3.31,1.89Z"/><polygon class="cls-1" points="15.31 7.28 12 9.17 8.69 7.28 12 5.39 15.31 7.28"/></svg>
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