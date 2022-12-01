
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="10.09" r="8.59"/><circle class="cls-1" cx="12" cy="10.09" r="2.86"/><line class="cls-1" x1="19.64" y1="22.5" x2="4.36" y2="22.5"/><polyline class="cls-1" points="15.82 17.79 15.82 22.5 8.18 22.5 8.18 17.79"/><line class="cls-1" x1="11.05" y1="4.36" x2="12.95" y2="4.36"/></svg>
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