
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.48" y="1.5" width="21.04" height="15.3"/><line class="cls-1" x1="0.52" y1="21.59" x2="10.09" y2="21.59"/><line class="cls-1" x1="10.09" y1="19.67" x2="10.09" y2="23.5"/><line class="cls-1" x1="23.48" y1="21.59" x2="12.96" y2="21.59"/><polygon class="cls-1" points="15.83 9.15 8.17 12.98 8.17 5.33 15.83 9.15"/></svg>
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