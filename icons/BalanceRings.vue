
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="0.55" y1="1.5" x2="23.45" y2="1.5"/><circle class="cls-1" cx="5.32" cy="18.68" r="3.82"/><circle class="cls-1" cx="18.68" cy="18.68" r="3.82"/><line class="cls-1" x1="5.32" y1="1.5" x2="5.32" y2="16.77"/><line class="cls-1" x1="18.68" y1="1.5" x2="18.68" y2="16.77"/></svg>
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