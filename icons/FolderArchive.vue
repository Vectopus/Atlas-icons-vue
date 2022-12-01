
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="19.64 9.14 4.36 9.14 4.36 1.5 10.09 1.5 12 3.41 19.64 3.41 19.64 9.14"/><polygon class="cls-1" points="1.5 9.14 22.5 9.14 20.59 22.5 3.41 22.5 1.5 9.14"/></svg>
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