
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="2.45" y="16.77" width="3.82" height="5.73"/><rect class="cls-1" x="17.73" y="9.14" width="3.82" height="13.36"/><rect class="cls-1" x="10.09" y="12.95" width="3.82" height="9.55"/><line class="cls-1" x1="0.55" y1="22.5" x2="23.45" y2="22.5"/><circle class="cls-1" cx="11.05" cy="5.32" r="3.82"/><line class="cls-1" x1="4.36" y1="12" x2="8.18" y2="8.18"/></svg>
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