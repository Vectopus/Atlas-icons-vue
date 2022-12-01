
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="1.5" width="21" height="21"/><rect class="cls-1" x="5.32" y="9.14" width="13.36" height="9.55"/><line class="cls-1" x1="4.36" y1="5.32" x2="10.09" y2="5.32"/><line class="cls-1" x1="17.73" y1="5.32" x2="19.64" y2="5.32"/><line class="cls-1" x1="13.91" y1="5.32" x2="15.82" y2="5.32"/><line class="cls-1" x1="10.09" y1="12" x2="8.18" y2="15.82"/><line class="cls-1" x1="14.86" y1="12" x2="12.95" y2="15.82"/></svg>
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