
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="16.77 1.5 16.77 7.23 11.04 7.23 11.04 12 6.27 12 6.27 16.77 1.5 16.77 1.5 22.5 22.5 22.5 22.5 14.86 22.5 8.18 22.5 7.23 22.5 1.5 16.77 1.5"/></svg>
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