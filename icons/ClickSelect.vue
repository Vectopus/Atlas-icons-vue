
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="12" y1="0.5" x2="12" y2="5.29"/><line class="cls-1" x1="12" y1="18.71" x2="12" y2="23.5"/><line class="cls-1" x1="23.5" y1="12" x2="18.71" y2="12"/><line class="cls-1" x1="5.29" y1="12" x2="0.5" y2="12"/><line class="cls-1" x1="20.13" y1="3.87" x2="16.74" y2="7.26"/><line class="cls-1" x1="7.26" y1="16.74" x2="3.87" y2="20.13"/><line class="cls-1" x1="20.13" y1="20.13" x2="16.74" y2="16.74"/><line class="cls-1" x1="7.26" y1="7.26" x2="3.87" y2="3.87"/></svg>
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