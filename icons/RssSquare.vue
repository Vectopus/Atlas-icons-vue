
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M6.27,11.05A6.68,6.68,0,0,1,13,17.73"/><path class="cls-1" d="M6.27,6.27A11.46,11.46,0,0,1,17.73,17.73"/><circle class="cls-1" cx="7.23" cy="16.77" r="0.95"/><rect class="cls-1" x="1.5" y="1.5" width="21" height="21"/></svg>
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