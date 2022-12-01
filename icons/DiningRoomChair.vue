
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="5.29" y="12.96" width="13.42" height="3.83" rx="1.92"/><line class="cls-1" x1="7.21" y1="23.5" x2="7.21" y2="16.79"/><line class="cls-1" x1="16.79" y1="23.5" x2="16.79" y2="16.79"/><line class="cls-1" x1="7.21" y1="20.63" x2="16.79" y2="20.63"/><polyline class="cls-1" points="16.79 0.5 16.79 12.96 7.21 12.96 7.21 0.5"/><line class="cls-1" x1="7.21" y1="3.38" x2="16.79" y2="3.38"/><line class="cls-1" x1="7.21" y1="7.21" x2="16.79" y2="7.21"/></svg>
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