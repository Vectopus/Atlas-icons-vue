
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><ellipse class="cls-1" cx="12" cy="12" rx="13.51" ry="6.14" transform="translate(-4.97 12) rotate(-45)"/><ellipse class="cls-1" cx="12" cy="12" rx="6.14" ry="13.51" transform="translate(-4.97 12) rotate(-45)"/><circle class="cls-1" cx="12" cy="12" r="0.95"/></svg>
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