
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="yuan_coin" data-name="yuan coin"><circle class="cls-1" cx="12" cy="12" r="10.5"/><polyline class="cls-1" points="15.82 7.23 12 12 8.18 7.23"/><line class="cls-1" x1="12" y1="18.68" x2="12" y2="12"/><line class="cls-1" x1="9.14" y1="12.95" x2="14.86" y2="12.95"/></g></svg>
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