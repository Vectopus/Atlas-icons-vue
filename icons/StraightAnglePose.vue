
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="9.1" r="1.92"/><polyline class="cls-1" points="0.5 20.6 10.08 20.6 10.08 12.94 13.92 12.94 13.92 20.6 23.5 20.6"/><polyline class="cls-1" points="13.92 12.94 14.88 12.94 17.75 9.1 17.75 8.15 13.92 4.31 13.92 2.4"/><polyline class="cls-1" points="10.08 12.94 9.13 12.94 6.25 9.1 6.25 8.15 10.08 4.31 10.08 2.4"/></svg>
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