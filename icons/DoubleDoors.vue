
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="2.45" y="1.5" width="9.55" height="21"/><rect class="cls-1" x="12" y="1.5" width="9.55" height="21"/><line class="cls-1" x1="23.45" y1="22.5" x2="0.55" y2="22.5"/><line class="cls-1" x1="7.23" y1="12.95" x2="10.09" y2="12.95"/><line class="cls-1" x1="13.91" y1="12.95" x2="16.77" y2="12.95"/></svg>
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