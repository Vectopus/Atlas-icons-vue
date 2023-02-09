
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="10.11" r="8.61"/><circle class="cls-1" cx="12" cy="10.11" r="4.78"/><circle class="cls-1" cx="12" cy="10.11" r="0.96"/><line class="cls-1" x1="16.78" y1="23.5" x2="15.87" y2="17.79"/><line class="cls-1" x1="8.13" y1="17.79" x2="7.22" y2="23.5"/><line class="cls-1" x1="7.22" y1="21.59" x2="16.78" y2="21.59"/></svg>
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