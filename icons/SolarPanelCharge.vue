
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="21.5 11.95 2.5 11.95 6.3 1.5 17.7 1.5 21.5 11.95"/><polyline class="cls-1" points="5.26 4.35 9.58 4.35 14.42 4.35 18.73 4.35"/><polyline class="cls-1" points="3.88 8.15 8.89 8.15 15.11 8.15 20.12 8.15"/><line class="cls-1" x1="10.1" y1="1.5" x2="8.2" y2="11.95"/><line class="cls-1" x1="13.9" y1="1.5" x2="15.8" y2="11.95"/><polygon class="cls-1" points="12 15.75 10.1 18.6 12 18.6 12 15.75"/><polygon class="cls-1" points="12 20.5 13.9 17.65 12 17.65 12 20.5"/></svg>
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