
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="0.55" y1="22.5" x2="23.45" y2="22.5"/><rect class="cls-1" x="2.45" y="1.5" width="9.55" height="10.5"/><rect class="cls-1" x="12" y="1.5" width="9.55" height="10.5"/><rect class="cls-1" x="2.45" y="12" width="9.55" height="10.5"/><rect class="cls-1" x="12" y="12" width="9.55" height="10.5"/></svg>
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