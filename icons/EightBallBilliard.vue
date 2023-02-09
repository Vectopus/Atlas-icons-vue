
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="12" r="10.5"/><circle class="cls-1" cx="12" cy="12" r="10.5"/><circle class="cls-1" cx="12" cy="12" r="10.5"/><circle class="cls-1" cx="12" cy="10.09" r="1.91"/><circle class="cls-1" cx="12" cy="13.91" r="1.91"/><circle class="cls-1" cx="12" cy="12" r="6.68"/></svg>
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