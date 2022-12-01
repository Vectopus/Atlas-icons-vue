
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="4.36" width="21" height="15.27"/><rect class="cls-1" x="13.91" y="8.18" width="4.77" height="3.82"/><line class="cls-1" x1="12.95" y1="15.82" x2="19.64" y2="15.82"/><line class="cls-1" x1="4.36" y1="8.18" x2="9.14" y2="8.18"/><line class="cls-1" x1="4.36" y1="12" x2="9.14" y2="12"/><line class="cls-1" x1="4.36" y1="15.82" x2="9.14" y2="15.82"/></svg>
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