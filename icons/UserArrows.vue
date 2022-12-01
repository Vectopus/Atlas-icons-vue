
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="12" r="8"/><circle class="cls-1" cx="12" cy="11" r="3"/><path class="cls-1" d="M16.94,18.29a5,5,0,0,0-9.88,0"/><polyline class="cls-1" points="6 1 3 4 12 4"/><polyline class="cls-1" points="18 23 21 20 12 20"/></svg>
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