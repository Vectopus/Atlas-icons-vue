
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="3.41" cy="5.32" r="1.91"/><circle class="cls-1" cx="12" cy="18.68" r="1.91"/><circle class="cls-1" cx="20.59" cy="12" r="1.91"/><line class="cls-1" x1="3.41" y1="23.45" x2="3.41" y2="7.23"/><line class="cls-1" x1="3.41" y1="3.41" x2="3.41" y2="0.55"/><line class="cls-1" x1="12" y1="23.45" x2="12" y2="20.59"/><line class="cls-1" x1="12" y1="16.77" x2="12" y2="0.55"/><line class="cls-1" x1="20.59" y1="23.45" x2="20.59" y2="13.91"/><line class="cls-1" x1="20.59" y1="10.09" x2="20.59" y2="0.55"/></svg>
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