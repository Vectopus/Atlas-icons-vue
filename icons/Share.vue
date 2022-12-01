
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="19.64" cy="4.36" r="2.86"/><circle class="cls-1" cx="4.36" cy="12" r="2.86"/><circle class="cls-1" cx="19.64" cy="19.64" r="2.86"/><line class="cls-1" x1="17.08" y1="5.64" x2="6.92" y2="10.72"/><line class="cls-1" x1="17.08" y1="18.36" x2="6.92" y2="13.28"/></svg>
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