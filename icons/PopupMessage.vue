
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="4.35" cy="3.89" r="2.39"/><polyline class="cls-1" points="6.26 23.5 6.26 15.85 7.22 14.89 7.22 8.2 1.48 8.2 1.48 14.89 2.44 15.85 2.44 23.5"/><polygon class="cls-1" points="11.04 1.5 11.04 3.41 9.13 5.33 11.04 7.24 11.04 9.15 22.52 9.15 22.52 1.5 11.04 1.5"/><circle class="cls-1" cx="14.87" cy="5.33"/><circle class="cls-1" cx="18.7" cy="5.33"/></svg>
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