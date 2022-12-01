
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="4.36" width="21" height="15.27" rx="1.91"/><line class="cls-1" x1="1.5" y1="8.18" x2="22.5" y2="8.18"/><circle class="cls-1" cx="16.77" cy="13.91" r="1.91"/><polyline class="cls-1" points="5.32 16.77 5.32 13.91 14.86 13.91"/><line class="cls-1" x1="9.14" y1="16.77" x2="9.14" y2="13.91"/></svg>
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