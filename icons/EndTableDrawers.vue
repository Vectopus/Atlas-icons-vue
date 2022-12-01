
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="0.5" y1="3.4" x2="23.5" y2="3.4"/><rect class="cls-1" x="3.38" y="3.4" width="8.63" height="6.71"/><rect class="cls-1" x="12" y="3.4" width="8.63" height="6.71"/><line class="cls-1" x1="4.33" y1="21.6" x2="4.33" y2="16.81"/><line class="cls-1" x1="19.67" y1="21.6" x2="19.67" y2="16.81"/><line class="cls-1" x1="6.25" y1="6.27" x2="9.13" y2="6.27"/><line class="cls-1" x1="14.88" y1="6.27" x2="17.75" y2="6.27"/><rect class="cls-1" x="3.38" y="10.1" width="8.63" height="6.71"/><rect class="cls-1" x="12" y="10.1" width="8.63" height="6.71"/><line class="cls-1" x1="6.25" y1="12.98" x2="9.13" y2="12.98"/><line class="cls-1" x1="14.88" y1="12.98" x2="17.75" y2="12.98"/></svg>
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