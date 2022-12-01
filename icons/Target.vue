
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="target"><circle class="cls-1" cx="12" cy="12" r="10.5"/><circle class="cls-1" cx="12" cy="12" r="5.73"/><line class="cls-1" x1="12" y1="8.18" x2="12" y2="4.36"/><line class="cls-1" x1="12" y1="19.64" x2="12" y2="15.82"/><line class="cls-1" x1="8.18" y1="12" x2="4.36" y2="12"/><line class="cls-1" x1="19.64" y1="12" x2="15.82" y2="12"/></g></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-linecap:square;stroke-miterlimit:10;}
</style>