
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="5.32" width="21" height="17.18"/><circle class="cls-1" cx="13.91" cy="13.91" r="4.77"/><polyline class="cls-1" points="1.5 5.32 3.41 1.5 10.09 1.5 12 5.32"/><line class="cls-1" x1="4.36" y1="9.14" x2="6.27" y2="9.14"/><line class="cls-1" x1="4.36" y1="12.95" x2="6.27" y2="12.95"/></svg>
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