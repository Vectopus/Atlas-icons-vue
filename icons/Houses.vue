
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="12.96 11.04 12.96 18.68 1.5 18.68 1.5 11.04 7.23 5.32 12.96 11.04"/><polygon class="cls-1" points="17.73 11.04 17.73 18.68 12.96 18.68 12.96 11.04 9.61 7.71 12 5.32 17.73 11.04"/><polygon class="cls-1" points="22.5 11.04 22.5 18.68 17.73 18.68 17.73 11.04 14.39 7.71 16.77 5.32 22.5 11.04"/><rect class="cls-1" x="5.32" y="13.91" width="3.82" height="4.77"/></svg>
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