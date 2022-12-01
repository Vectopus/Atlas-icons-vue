
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="17.73" width="21" height="3.82"/><path class="cls-1" d="M12,7.23h0a9.55,9.55,0,0,1,9.55,9.55v1a0,0,0,0,1,0,0H2.45a0,0,0,0,1,0,0v-1A9.55,9.55,0,0,1,12,7.23Z"/><circle class="cls-1" cx="12" cy="3.41" r="0.95"/><line class="cls-1" x1="12" y1="7.23" x2="12" y2="4.36"/></svg>
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