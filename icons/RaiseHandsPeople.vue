
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="4.33" cy="3.85" r="2.4"/><polyline class="cls-1" points="6.25 23.5 6.25 15.83 7.21 14.88 7.21 8.17 1.46 8.17 1.46 14.88 2.42 15.83 2.42 23.5"/><circle class="cls-1" cx="19.67" cy="3.85" r="2.4"/><polyline class="cls-1" points="21.58 23.5 21.58 15.83 22.54 14.88 22.54 8.17 16.79 8.17 16.79 14.88 17.75 15.83 17.75 23.5"/><polyline class="cls-1" points="16.79 8.17 15.83 8.17 12.96 2.42 12.96 0.5"/><polyline class="cls-1" points="7.21 8.17 8.17 8.17 11.04 2.42 11.04 0.5"/></svg>
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