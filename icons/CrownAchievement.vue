
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="8.18" y="12.98" width="7.64" height="9.55"/><rect class="cls-1" x="15.82" y="16.8" width="6.68" height="5.73"/><rect class="cls-1" x="1.5" y="18.7" width="6.68" height="3.82"/><polygon class="cls-1" points="16.77 9.16 7.23 9.16 7.23 3.43 10.09 4.39 12 2.48 13.91 4.39 16.77 3.43 16.77 9.16"/><line class="cls-1" x1="5.32" y1="9.16" x2="18.68" y2="9.16"/></svg>
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