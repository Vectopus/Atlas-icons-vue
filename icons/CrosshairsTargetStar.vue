
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="12 8.17 13.25 10.69 16.03 11.1 14.02 13.06 14.49 15.83 12 14.52 9.51 15.83 9.98 13.06 7.97 11.1 10.75 10.69 12 8.17"/><line class="cls-1" x1="12" y1="0.5" x2="12" y2="5.29"/><line class="cls-1" x1="12" y1="18.71" x2="12" y2="23.5"/><line class="cls-1" x1="23.5" y1="12" x2="18.71" y2="12"/><line class="cls-1" x1="5.29" y1="12" x2="0.5" y2="12"/><circle class="cls-1" cx="12" cy="12" r="9.58"/></svg>
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