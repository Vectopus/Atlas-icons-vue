
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.48" y="1.5" width="21.04" height="19.13"/><line class="cls-1" x1="12" y1="1.5" x2="12" y2="20.63"/><line class="cls-1" x1="9.13" y1="10.11" x2="9.13" y2="12.02"/><line class="cls-1" x1="14.87" y1="10.11" x2="14.87" y2="12.02"/><line class="cls-1" x1="3.39" y1="23.5" x2="3.39" y2="20.63"/><line class="cls-1" x1="20.61" y1="23.5" x2="20.61" y2="20.63"/></svg>
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