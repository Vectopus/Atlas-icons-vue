
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="7.23" width="17.18" height="13.36"/><polygon class="cls-1" points="4.36 3.41 4.36 7.23 18.68 7.23 18.68 16.77 22.5 16.77 22.5 3.41 4.36 3.41"/><polyline class="cls-1" points="1.5 7.04 9.9 15.44 18.3 7.04"/><line class="cls-1" x1="8.18" y1="13.72" x2="1.5" y2="20.4"/><line class="cls-1" x1="18.3" y1="20.4" x2="11.62" y2="13.72"/></svg>
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