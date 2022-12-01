
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="2.43" width="21" height="4.77"/><rect class="cls-1" x="1.5" y="7.2" width="21" height="15.27"/><line class="cls-1" x1="6.27" y1="0.52" x2="6.27" y2="4.34"/><line class="cls-1" x1="17.73" y1="0.52" x2="17.73" y2="4.34"/><line class="cls-1" x1="12" y1="0.52" x2="12" y2="4.34"/><line class="cls-1" x1="12" y1="16.75" x2="12" y2="19.61"/><polygon class="cls-1" points="13.91 16.59 10.09 16.59 12 13.89 13.91 16.59"/><polygon class="cls-1" points="13.91 14.84 10.09 14.84 12 11.98 13.91 14.84"/><polygon class="cls-1" points="12.96 11.98 11.04 11.98 12 11.02 12.96 11.98"/></svg>
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