
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="1.5" width="21" height="17.18" rx="1.91"/><rect class="cls-1" x="1.5" y="1.5" width="21" height="21" rx="1.91"/><circle class="cls-1" cx="12" cy="5.32" r="3.82"/><line class="cls-1" x1="12" y1="4.36" x2="12" y2="9.14"/><line class="cls-1" x1="12" y1="12" x2="12" y2="18.68"/></svg>
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