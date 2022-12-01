
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="1.5" width="21" height="21"/><line class="cls-1" x1="4.36" y1="17.73" x2="12.95" y2="17.73"/><line class="cls-1" x1="12.95" y1="15.82" x2="12.95" y2="19.64"/><line class="cls-1" x1="15.82" y1="17.73" x2="19.64" y2="17.73"/><polygon class="cls-1" points="9.14 12 9.14 6.27 14.86 9.14 9.14 12"/></svg>
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