
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="6.27" y="1.5" width="11.45" height="17.18"/><polygon class="cls-1" points="6.27 18.68 17.73 18.68 20.59 22.5 3.41 22.5 6.27 18.68"/><polyline class="cls-1" points="6.27 18.68 13.91 15.82 13.91 1.5"/><line class="cls-1" x1="11.05" y1="8.18" x2="11.05" y2="10.09"/></svg>
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