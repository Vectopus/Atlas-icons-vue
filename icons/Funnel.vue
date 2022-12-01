
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="7.23 1.48 7.23 6.25 12.96 12.93 12.96 21.52 16.77 19.61 16.77 12.93 22.5 6.25 22.5 1.48 7.23 1.48"/><circle class="cls-1" cx="4.36" cy="4.34" r="2.86"/><line class="cls-1" x1="19.64" y1="5.3" x2="7.23" y2="5.3"/></svg>
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