
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="3.38" y1="23.5" x2="3.38" y2="7.21"/><line class="cls-1" x1="3.38" y1="4.33" x2="3.38" y2="0.5"/><line class="cls-1" x1="12" y1="23.5" x2="12" y2="19.67"/><line class="cls-1" x1="12" y1="16.79" x2="12" y2="0.5"/><line class="cls-1" x1="20.63" y1="23.5" x2="20.63" y2="13.92"/><line class="cls-1" x1="20.63" y1="11.04" x2="20.63" y2="0.5"/><line class="cls-1" x1="0.5" y1="4.33" x2="6.25" y2="4.33"/><line class="cls-1" x1="9.13" y1="16.79" x2="14.88" y2="16.79"/><line class="cls-1" x1="17.75" y1="11.04" x2="23.5" y2="11.04"/></svg>
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