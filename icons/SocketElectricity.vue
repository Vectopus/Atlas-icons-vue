
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="1.5" width="21" height="21" rx="1.91"/><circle class="cls-1" cx="12" cy="12" r="6.68"/><circle class="cls-2" cx="4.36" cy="4.36" r="0.95"/><circle class="cls-2" cx="19.64" cy="4.36" r="0.95"/><circle class="cls-2" cx="19.64" cy="19.64" r="0.95"/><circle class="cls-2" cx="4.36" cy="19.64" r="0.95"/><circle class="cls-2" cx="9.14" cy="12" r="0.95"/><circle class="cls-2" cx="14.86" cy="12" r="0.95"/></svg>
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