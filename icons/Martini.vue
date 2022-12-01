
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="12 13.91 2.46 1.5 21.55 1.5 12 13.91"/><path class="cls-1" d="M5.32,5.32C12,3.41,12,7.23,18.68,5.32"/><line class="cls-1" x1="12" y1="22.5" x2="12" y2="13.91"/><line class="cls-1" x1="15.82" y1="22.5" x2="8.18" y2="22.5"/></svg>
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