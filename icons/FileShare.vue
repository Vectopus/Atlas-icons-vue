
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="9.14" cy="14.86" r="0.95"/><circle class="cls-1" cx="14.86" cy="12" r="0.95"/><circle class="cls-1" cx="14.86" cy="17.73" r="0.95"/><line class="cls-1" x1="9.14" y1="14.86" x2="14.86" y2="17.73"/><line class="cls-1" x1="14.86" y1="12" x2="9.14" y2="14.86"/><polygon class="cls-1" points="20.59 6.27 20.59 22.5 3.41 22.5 3.41 1.5 15.82 1.5 20.59 6.27"/><polygon class="cls-1" points="20.59 6.27 20.59 7.23 14.86 7.23 14.86 1.5 15.82 1.5 20.59 6.27"/></svg>
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