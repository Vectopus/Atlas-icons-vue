
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="6.27" y="1.5" width="11.45" height="21" rx="1.91"/><circle class="cls-1" cx="12" cy="17.73" r="0.95"/><line class="cls-1" x1="12" y1="4.36" x2="12" y2="16.77"/><line class="cls-1" x1="10.09" y1="6.27" x2="12" y2="6.27"/><line class="cls-1" x1="10.09" y1="10.09" x2="12" y2="10.09"/><line class="cls-1" x1="10.09" y1="13.91" x2="12" y2="13.91"/></svg>
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