
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="12" r="10.5"/><line class="cls-1" x1="12.95" y1="11.05" x2="6.27" y2="17.73"/><polyline class="cls-1" points="10.09 7.23 16.77 7.23 16.77 13.91"/><polyline class="cls-1" points="6.27 11.04 12.96 11.04 12.96 17.73"/></svg>
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