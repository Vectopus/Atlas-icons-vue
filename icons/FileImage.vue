
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="17.73 17.73 10.36 17.73 11.16 16.47 14.04 12 17.73 17.73"/><polygon class="cls-1" points="11.16 16.47 10.36 17.73 6.27 17.73 9.14 13.43 11.16 16.47"/><circle class="cls-2" cx="9.61" cy="10.57" r="0.48"/><polygon class="cls-2" points="20.59 6.27 20.59 22.5 3.41 22.5 3.41 1.5 15.82 1.5 20.59 6.27"/><polygon class="cls-2" points="20.59 6.27 20.59 7.23 14.86 7.23 14.86 1.5 15.82 1.5 20.59 6.27"/></svg>
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
    .cls-1{fill:currentColor;}.cls-2{fill:none;stroke:currentColor;stroke-miterlimit:10;}
</style>