
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="6.27" y1="14.86" x2="13.91" y2="14.86"/><line class="cls-1" x1="6.27" y1="11.05" x2="13.91" y2="11.05"/><line class="cls-1" x1="6.27" y1="18.68" x2="13.91" y2="18.68"/><polygon class="cls-1" points="16.77 8.18 16.77 22.5 3.41 22.5 3.41 5.32 13.91 5.32 16.77 8.18"/><polyline class="cls-1" points="16.77 18.68 20.59 18.68 20.59 4.36 17.73 1.5 7.23 1.5 7.23 5.32"/></svg>
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