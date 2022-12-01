
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><ellipse class="cls-1" cx="12" cy="12" rx="3.82" ry="10.5"/><ellipse class="cls-1" cx="12" cy="12" rx="3.82" ry="10.5" transform="translate(-4.39 16.39) rotate(-60)"/><ellipse class="cls-1" cx="12" cy="12" rx="10.5" ry="3.82" transform="translate(-4.39 7.61) rotate(-30)"/></svg>
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