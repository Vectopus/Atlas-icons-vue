
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="5.32" width="5.73" height="17.18"/><polygon class="cls-1" points="22.5 1.5 22.5 7.23 7.23 7.23 7.23 5.32 1.5 5.32 1.5 1.5 22.5 1.5"/><line class="cls-1" x1="11.05" y1="4.36" x2="11.05" y2="7.23"/><line class="cls-1" x1="14.86" y1="4.36" x2="14.86" y2="7.23"/><line class="cls-1" x1="18.68" y1="4.36" x2="18.68" y2="7.23"/></svg>
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