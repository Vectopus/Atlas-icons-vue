
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="4.36" y="1.5" width="15.27" height="21" rx="1.91"/><rect class="cls-1" x="8.18" y="5.32" width="7.64" height="3.82"/><circle class="cls-2" cx="12" cy="18.68" r="0.95"/><line class="cls-1" x1="8.18" y1="12.95" x2="15.82" y2="12.95"/></svg>
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