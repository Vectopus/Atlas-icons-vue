
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="23.5 22.5 1.5 22.5 1.5 17.55 1.5 0.5"/><polyline class="cls-1" points="22.54 16.76 12.98 7.2 9.15 11.02 1.5 3.37"/><polyline class="cls-1" points="17.76 16.76 22.54 16.76 22.54 11.98"/></svg>
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