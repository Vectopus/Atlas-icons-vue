
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="1.5" width="21" height="21" rx="1.91"/><circle class="cls-1" cx="12" cy="12" r="7.64"/><polygon class="cls-2" points="13.43 9.14 10.57 9.14 12 6.27 13.43 9.14"/><polygon class="cls-2" points="10.57 14.86 13.43 14.86 12 17.73 10.57 14.86"/><polygon class="cls-2" points="14.86 13.43 14.86 10.57 17.73 12 14.86 13.43"/><polygon class="cls-2" points="9.14 10.57 9.14 13.43 6.27 12 9.14 10.57"/><circle class="cls-1" cx="12" cy="12" r="0.95"/></svg>
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