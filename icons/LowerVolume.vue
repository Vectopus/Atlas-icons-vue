
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="16.77" y1="12" x2="22.5" y2="12"/><rect class="cls-1" x="1.5" y="8.18" width="4.77" height="7.64"/><polygon class="cls-1" points="13.91 3.41 13.91 20.59 12.24 20.59 6.27 15.82 6.27 8.18 12.24 3.41 13.91 3.41"/></svg>
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