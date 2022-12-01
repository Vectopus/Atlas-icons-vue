
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="3.41" y="1.5" width="17.18" height="21" rx="1.91"/><circle class="cls-1" cx="12" cy="10.09" r="4.77"/><line class="cls-1" x1="13.43" y1="11.52" x2="16.3" y2="14.39"/><circle class="cls-2" cx="12" cy="10.09" r="0.95"/><line class="cls-1" x1="7.23" y1="18.68" x2="16.77" y2="18.68"/></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-2{fill:currentColor;}
</style>