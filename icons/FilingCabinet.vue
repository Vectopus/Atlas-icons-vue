
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="archieve"><rect class="cls-1" x="1.5" y="1.98" width="21" height="6.68"/><rect class="cls-1" x="1.5" y="8.66" width="21" height="6.68"/><rect class="cls-1" x="1.5" y="15.34" width="21" height="6.68"/><line class="cls-1" x1="10.09" y1="3.89" x2="13.91" y2="3.89"/><line class="cls-1" x1="10.09" y1="10.57" x2="13.91" y2="10.57"/><line class="cls-1" x1="10.09" y1="17.25" x2="13.91" y2="17.25"/></g></svg>
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