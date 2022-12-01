
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="suitcase"><rect class="cls-1" x="1.5" y="6.27" width="21" height="15.27" rx="2"/><polygon class="cls-1" points="15.82 6.27 8.18 6.27 9.14 2.46 14.86 2.46 15.82 6.27"/><line class="cls-1" x1="6.27" y1="6.27" x2="6.27" y2="21.55"/><line class="cls-1" x1="17.73" y1="6.27" x2="17.73" y2="21.55"/></g></svg>
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