
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="15.82 11.04 12 14.86 8.18 11.04"/><polyline class="cls-1" points="14.86 1.5 16.77 1.5 20.59 5.32 20.59 6.27 20.59 22.5 15.82 22.5 12 22.5 3.41 22.5 3.41 1.5 8.18 1.5 12 1.5 12 14.86"/></svg>
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