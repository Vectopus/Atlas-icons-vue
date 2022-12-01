
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="5.32" y="17.73" width="13.36" height="4.77"/><rect class="cls-1" x="5.32" y="12.95" width="13.36" height="4.77"/><line class="cls-1" x1="12" y1="19.64" x2="12" y2="17.73"/><line class="cls-1" x1="12" y1="14.86" x2="12" y2="6.27"/><line class="cls-1" x1="20.59" y1="12.95" x2="3.41" y2="12.95"/><polygon class="cls-1" points="14.86 6.27 9.14 6.27 10.09 1.5 13.91 1.5 14.86 6.27"/><line class="cls-1" x1="9.14" y1="12" x2="14.86" y2="12"/></svg>
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