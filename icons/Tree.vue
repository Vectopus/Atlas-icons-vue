
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="12" y1="5.32" x2="12" y2="22.5"/><line class="cls-1" x1="15.82" y1="22.5" x2="8.18" y2="22.5"/><line class="cls-1" x1="9.14" y1="10.09" x2="12" y2="12"/><circle class="cls-1" cx="12" cy="8.18" r="6.68"/><line class="cls-1" x1="14.86" y1="7.23" x2="12" y2="10.09"/></svg>
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