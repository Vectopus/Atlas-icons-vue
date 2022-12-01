
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="19.64 6.27 4.36 6.27 4.36 2.46 8.18 1.5 15.82 1.5 19.64 2.46 19.64 6.27"/><rect class="cls-1" x="9.14" y="1.5" width="5.73" height="21"/><line class="cls-1" x1="12" y1="10.09" x2="14.86" y2="10.09"/><line class="cls-1" x1="12.95" y1="13.91" x2="14.86" y2="13.91"/><line class="cls-1" x1="12" y1="17.73" x2="14.86" y2="17.73"/></svg>
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