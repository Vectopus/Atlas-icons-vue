
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="price_tag" data-name="price tag"><polygon class="cls-1" points="3.41 1.5 1.5 3.41 1.5 11.04 12.96 22.5 22.5 12.96 11.04 1.5 3.41 1.5"/><circle class="cls-2" cx="6.27" cy="6.27" r="1.91"/></g></svg>
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
    .cls-1,.cls-2{fill:none;stroke:currentColor;}.cls-1{stroke-miterlimit:10;}.cls-2{stroke-linecap:round;stroke-linejoin:round;}
</style>