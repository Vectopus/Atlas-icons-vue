
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="12" r="6.71"/><line class="cls-1" x1="12" y1="0.5" x2="12" y2="3.38"/><line class="cls-1" x1="12" y1="20.63" x2="12" y2="23.5"/><line class="cls-1" x1="23.5" y1="12" x2="20.63" y2="12"/><line class="cls-1" x1="3.38" y1="12" x2="0.5" y2="12"/><line class="cls-1" x1="20.13" y1="3.87" x2="18.1" y2="5.9"/><line class="cls-1" x1="5.9" y1="18.1" x2="3.87" y2="20.13"/><line class="cls-1" x1="20.13" y1="20.13" x2="18.1" y2="18.1"/><line class="cls-1" x1="5.9" y1="5.9" x2="3.87" y2="3.87"/><polygon class="cls-1" points="12 11.04 11.28 12 12 12 12 11.04"/><polygon class="cls-1" points="12 12.96 12.72 12 12 12 12 12.96"/></svg>
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