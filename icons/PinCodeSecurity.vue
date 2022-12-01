
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="1.48" width="21" height="8.59"/><circle class="cls-1" cx="4.84" cy="5.77" r="0.48"/><circle class="cls-1" cx="9.61" cy="5.77" r="0.48"/><circle class="cls-1" cx="14.39" cy="5.77" r="0.48"/><circle class="cls-1" cx="19.16" cy="5.77" r="0.48"/><line class="cls-1" x1="10.09" y1="13.89" x2="13.91" y2="13.89"/><line class="cls-1" x1="15.82" y1="13.89" x2="19.64" y2="13.89"/><line class="cls-1" x1="4.36" y1="13.89" x2="8.18" y2="13.89"/><line class="cls-1" x1="10.09" y1="17.7" x2="13.91" y2="17.7"/><line class="cls-1" x1="15.82" y1="17.7" x2="19.64" y2="17.7"/><line class="cls-1" x1="4.36" y1="17.7" x2="8.18" y2="17.7"/><line class="cls-1" x1="10.09" y1="21.52" x2="13.91" y2="21.52"/><line class="cls-1" x1="15.82" y1="21.52" x2="19.64" y2="21.52"/><line class="cls-1" x1="4.36" y1="21.52" x2="8.18" y2="21.52"/></svg>
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