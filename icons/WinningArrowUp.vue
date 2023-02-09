
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="18.69" width="5.71" height="3.81"/><rect class="cls-1" x="7.21" y="14.88" width="5.71" height="7.62"/><polygon class="cls-1" points="15.79 2.5 10.07 10.12 12.93 10.12 12.93 22.5 18.64 22.5 18.64 10.12 21.5 10.12 15.79 2.5"/></svg>
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