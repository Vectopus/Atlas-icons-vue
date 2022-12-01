
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="19.62 22 12 18.19 4.38 22 4.38 2 19.62 2 19.62 22"/><polygon class="cls-1" points="12 7.84 12.59 9.03 13.9 9.22 12.95 10.15 13.18 11.46 12 10.84 10.82 11.46 11.05 10.15 10.1 9.22 11.41 9.03 12 7.84"/></svg>
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