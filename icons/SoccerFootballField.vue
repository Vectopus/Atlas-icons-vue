
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="3.41" width="21" height="17.18"/><rect class="cls-1" x="18.68" y="9.14" width="3.82" height="5.73"/><rect class="cls-1" x="1.5" y="9.14" width="3.82" height="5.73"/><circle class="cls-1" cx="12" cy="12" r="2.86"/><line class="cls-1" x1="12" y1="3.41" x2="12" y2="9.14"/><line class="cls-1" x1="12" y1="14.86" x2="12" y2="20.59"/></svg>
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