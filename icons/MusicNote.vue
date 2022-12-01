
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M11.4,21c-1.68,1.7-4.08,2.06-5.32.8s-.9-3.63.8-5.32,4.07-2,5.32-.8S13.1,19.31,11.4,21Z"/><path class="cls-1" d="M18.67,11v-1C18.67,5.31,13,6.26,13,.54L13,18"/></svg>
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