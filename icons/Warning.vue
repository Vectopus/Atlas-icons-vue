
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="16.35 1.5 7.65 1.5 1.5 7.65 1.5 16.35 7.65 22.5 16.35 22.5 22.5 16.35 22.5 7.65 16.35 1.5"/><line class="cls-1" x1="12" y1="6.27" x2="12" y2="13.91"/><line class="cls-1" x1="12" y1="15.82" x2="12" y2="17.73"/></svg>
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