
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="18.68 5.32 16.77 2.46 11.04 2.46 9.14 5.32 1.5 5.32 1.5 21.55 22.5 21.55 22.5 5.32 18.68 5.32"/><circle class="cls-1" cx="13.91" cy="12.95" r="4.77"/><line class="cls-1" x1="4.36" y1="9.14" x2="7.23" y2="9.14"/></svg>
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