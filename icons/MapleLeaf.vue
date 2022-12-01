
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="12 19.68 4.36 19.68 5.32 16.82 2.46 13.96 3.41 12.04 3.41 11.09 4.36 11.09 6.27 10.14 8.18 11.09 7.23 5.36 10.09 5.36 12 2.5 13.91 5.36 16.77 5.36 15.82 11.09 17.73 10.14 19.64 11.09 20.59 11.09 20.59 12.04 21.55 13.96 18.68 16.82 19.64 19.68 12 19.68"/><line class="cls-1" x1="12" y1="9.18" x2="12" y2="23.5"/><line class="cls-1" x1="6.27" y1="13.95" x2="12" y2="17.77"/><line class="cls-1" x1="17.73" y1="13" x2="12" y2="16.82"/></svg>
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