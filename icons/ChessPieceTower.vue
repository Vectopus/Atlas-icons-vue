
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="5.32" y="1.5" width="13.36" height="5.73"/><rect class="cls-1" x="9.14" y="1.5" width="0.95" height="1.91"/><rect class="cls-1" x="13.91" y="1.5" width="0.95" height="1.91"/><polygon class="cls-1" points="17.73 18.68 6.27 18.68 8.18 7.23 15.82 7.23 17.73 18.68"/><rect class="cls-1" x="4.36" y="18.68" width="15.27" height="3.82"/><line class="cls-1" x1="1.5" y1="22.5" x2="22.5" y2="22.5"/></svg>
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