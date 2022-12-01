
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="7 22.5 2 19.5 2 13.5 7 10.5 12 13.5 12 19.5 7 22.5"/><polygon class="cls-1" points="17 22.5 12 19.5 12 13.5 17 10.5 22 13.5 22 19.5 17 22.5"/><polygon class="cls-1" points="12 13.5 7 10.5 7 4.5 12 1.5 17 4.5 17 10.5 12 13.5"/></svg>
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