
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="organization"><circle class="cls-1" cx="12" cy="4.36" r="2.86"/><circle class="cls-1" cx="3.41" cy="20.59" r="1.91"/><circle class="cls-1" cx="12" cy="20.59" r="1.91"/><circle class="cls-1" cx="20.59" cy="20.59" r="1.91"/><polyline class="cls-1" points="3.41 18.68 3.41 12.96 20.59 12.96 20.59 18.68"/><line class="cls-1" x1="12" y1="18.68" x2="12" y2="7.23"/></g></svg>
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