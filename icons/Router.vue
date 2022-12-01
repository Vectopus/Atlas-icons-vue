
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="12.93" width="21" height="9.55"/><line class="cls-1" x1="5.32" y1="0.52" x2="5.32" y2="13.89"/><line class="cls-1" x1="18.68" y1="0.52" x2="18.68" y2="13.89"/><line class="cls-1" x1="19.64" y1="17.7" x2="17.73" y2="17.7"/><line class="cls-1" x1="15.82" y1="17.7" x2="13.91" y2="17.7"/><circle class="cls-1" cx="6.27" cy="17.7" r="0.95"/></svg>
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