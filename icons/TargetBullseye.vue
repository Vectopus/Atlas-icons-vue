
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="10.09" cy="12" r="8.59"/><circle class="cls-1" cx="10.09" cy="12" r="4.77"/><line class="cls-1" x1="10.09" y1="12" x2="20.59" y2="12"/><line class="cls-1" x1="22.5" y1="10.09" x2="20.59" y2="12"/><line class="cls-1" x1="22.5" y1="13.91" x2="20.59" y2="12"/><circle class="cls-1" cx="10.09" cy="12" r="0.95"/></svg>
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