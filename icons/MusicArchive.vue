
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="7.23" width="21" height="15.27"/><polygon class="cls-1" points="22.5 3.41 12 3.41 10.09 1.5 1.5 1.5 1.5 7.23 22.5 7.23 22.5 3.41"/><circle class="cls-1" cx="8.18" cy="17.73" r="0.95"/><circle class="cls-1" cx="13.91" cy="16.77" r="0.95"/><polyline class="cls-1" points="14.86 16.77 14.86 11.04 9.14 12 9.14 17.73"/></svg>
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