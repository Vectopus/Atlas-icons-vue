
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="7.76" y="1.39" width="8.49" height="21.21" transform="translate(12 28.97) rotate(-135)"/><line class="cls-1" x1="18.66" y1="11" x2="16.54" y2="8.88"/><line class="cls-1" x1="15.83" y1="13.83" x2="14.41" y2="12.41"/><line class="cls-1" x1="13" y1="16.66" x2="10.88" y2="14.54"/><line class="cls-1" x1="10.17" y1="19.49" x2="8.76" y2="18.07"/></svg>
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