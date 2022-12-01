
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="male"><circle class="cls-1" cx="9.14" cy="14.86" r="7.64"/><circle class="cls-1" cx="9.14" cy="14.86" r="3.82"/><line class="cls-1" x1="22.5" y1="1.5" x2="14.39" y2="9.61"/><polyline class="cls-1" points="12.96 1.5 22.5 1.5 22.5 11.04"/></g></svg>
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