
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="1.5" width="21" height="5.73"/><rect class="cls-1" x="1.5" y="7.23" width="21" height="15.27"/><line class="cls-1" x1="4.36" y1="4.36" x2="6.27" y2="4.36"/><line class="cls-1" x1="8.18" y1="4.36" x2="10.09" y2="4.36"/><line class="cls-1" x1="4.36" y1="18.68" x2="12" y2="18.68"/><line class="cls-1" x1="12" y1="16.77" x2="12" y2="20.59"/><line class="cls-1" x1="13.91" y1="18.68" x2="19.64" y2="18.68"/><polygon class="cls-1" points="12.96 12.48 10.09 13.91 10.09 11.04 12.96 12.48"/></svg>
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