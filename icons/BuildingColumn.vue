
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="bank"><polygon class="cls-1" points="22.5 6.27 22.5 9.14 1.5 9.14 1.5 6.27 12 1.5 22.5 6.27"/><rect class="cls-1" x="1.5" y="18.68" width="21" height="3.82"/><line class="cls-1" x1="3.41" y1="9.14" x2="3.41" y2="18.68"/><line class="cls-1" x1="9.14" y1="9.14" x2="9.14" y2="18.68"/><line class="cls-1" x1="14.86" y1="9.14" x2="14.86" y2="18.68"/><line class="cls-1" x1="20.59" y1="9.14" x2="20.59" y2="18.68"/></g></svg>
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