
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="briefcase_simple" data-name="briefcase simple"><rect class="cls-1" x="1.5" y="6.27" width="21" height="15.27" rx="1.91"/><path class="cls-2" d="M13.91,13h4.77A3.81,3.81,0,0,0,22.5,9.14v-1a1.91,1.91,0,0,0-1.91-1.91H3.41A1.91,1.91,0,0,0,1.5,8.18v1A3.81,3.81,0,0,0,5.32,13h8.59Z"/><line class="cls-1" x1="12" y1="12" x2="12" y2="13.91"/><polygon class="cls-1" points="15.82 6.27 8.18 6.27 9.14 2.46 14.86 2.46 15.82 6.27"/></g></svg>
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
    .cls-1,.cls-2{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-1{stroke-linecap:square;}
</style>