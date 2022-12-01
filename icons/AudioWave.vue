
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="23.45 11.04 21.55 11.04 18.68 17.73 17.73 17.73 17.73 6.27 16.77 6.27 12.96 22.5 12 22.5 12 1.5 11.04 1.5 7.23 17.73 6.27 17.73 6.27 6.27 6.27 6.27 5.32 6.27 2.46 11.04 0.55 11.04"/></svg>
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