
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="6.28" cy="6.27" r="4.77"/><circle class="cls-1" cx="17.73" cy="17.73" r="4.77"/><line class="cls-1" x1="17.73" y1="3.41" x2="17.73" y2="12.95"/><line class="cls-1" x1="6.28" y1="11.05" x2="6.28" y2="22.5"/><polyline class="cls-1" points="12.84 7.11 17.73 2.22 22.62 7.11"/><line class="cls-1" x1="1.5" y1="17.73" x2="11.05" y2="17.73"/></svg>
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