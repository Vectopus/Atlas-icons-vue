
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="aim"><circle class="cls-1" cx="12" cy="12" r="8.59"/><circle class="cls-1" cx="12" cy="12" r="2.86"/><line class="cls-1" x1="12" y1="5.32" x2="12" y2="1.5"/><line class="cls-1" x1="12" y1="22.5" x2="12" y2="18.68"/><line class="cls-1" x1="5.32" y1="12" x2="1.5" y2="12"/><line class="cls-1" x1="22.5" y1="12" x2="18.68" y2="12"/></g></svg>
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