
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="7.38 7.12 12 2.5 16.62 7.12"/><polyline class="cls-1" points="7.38 7.12 12 2.5 16.62 7.12"/><line class="cls-1" x1="12" y1="14.04" x2="12" y2="2.5"/><polyline class="cls-1" points="20.3 13.51 21.99 19.81 15.69 21.5"/><polyline class="cls-1" points="20.3 13.51 21.99 19.81 15.69 21.5"/><line class="cls-1" x1="21.99" y1="19.81" x2="12" y2="14.04"/><polyline class="cls-1" points="3.69 13.51 2.01 19.81 8.31 21.5"/><polyline class="cls-1" points="3.69 13.51 2.01 19.81 8.31 21.5"/><line class="cls-1" x1="12" y1="14.04" x2="2.01" y2="19.81"/></svg>
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