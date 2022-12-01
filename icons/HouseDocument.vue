
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="3.41" y="1.5" width="17.18" height="21"/><polyline class="cls-1" points="13.91 6.75 13.91 11.04 10.09 11.04 10.09 6.75"/><polyline class="cls-1" points="8.18 8.18 12 5.32 15.82 8.18"/><line class="cls-1" x1="7.23" y1="14.86" x2="16.77" y2="14.86"/><line class="cls-1" x1="7.23" y1="18.68" x2="16.77" y2="18.68"/></svg>
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