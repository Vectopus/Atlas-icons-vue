
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="drug"><rect class="cls-1" x="4.34" y="0.3" width="6.74" height="14.83" rx="3.37" transform="translate(7.71 -3.19) rotate(45)"/><circle class="cls-1" cx="16.76" cy="16.76" r="5.72"/><line class="cls-1" x1="20.77" y1="20.77" x2="12.95" y2="12.95"/><line class="cls-1" x1="10.09" y1="10.09" x2="5.33" y2="5.33"/></g></svg>
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