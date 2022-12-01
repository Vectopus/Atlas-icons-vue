
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="1.5" width="21" height="16.23" rx="1.91"/><polygon class="cls-1" points="15.82 22.5 8.18 22.5 9.14 17.73 14.86 17.73 15.82 22.5"/><line class="cls-1" x1="5.32" y1="22.5" x2="18.68" y2="22.5"/><circle class="cls-2" cx="12" cy="14.86" r="0.95"/></svg>
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