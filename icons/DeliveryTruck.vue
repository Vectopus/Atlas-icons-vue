
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="6.27" cy="17.73" r="1.91"/><circle class="cls-1" cx="17.73" cy="17.73" r="1.91"/><polyline class="cls-1" points="4.36 17.73 1.5 17.73 1.5 4.36 18.68 4.36 18.68 8.18 20.59 12 22.5 13.07 22.5 17.73 19.64 17.73"/><line class="cls-1" x1="15.82" y1="17.73" x2="8.18" y2="17.73"/><polyline class="cls-1" points="20.59 12 14.86 12 14.86 8.18 18.68 8.18"/></svg>
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