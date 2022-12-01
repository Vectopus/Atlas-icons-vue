
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="17.73" cy="17.73" r="4.77"/><line class="cls-1" x1="17.73" y1="3.41" x2="17.73" y2="12.95"/><polyline class="cls-1" points="13.32 6.63 17.73 2.22 22.14 6.63"/><circle class="cls-1" cx="6.27" cy="6.27" r="4.77"/><line class="cls-1" x1="6.27" y1="20.59" x2="6.27" y2="11.05"/><polyline class="cls-1" points="10.68 17.37 6.27 21.78 1.86 17.37"/></svg>
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