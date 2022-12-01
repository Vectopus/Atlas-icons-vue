
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="16.77 11.04 16.77 16.77 7.23 16.77 7.23 11.04 1.5 11.04 1.5 22.5 6.27 22.5 7.23 22.5 16.77 22.5 17.73 22.5 22.5 22.5 22.5 11.04 16.77 11.04"/><rect class="cls-1" x="9.14" y="0.55" width="5.73" height="7.64" transform="translate(7.64 16.36) rotate(-90)"/></svg>
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