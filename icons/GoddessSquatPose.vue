
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="3.85" r="2.39"/><polyline class="cls-1" points="3.39 22.5 5.3 22.5 5.3 15.8 10.09 15.8 10.09 8.15 13.91 8.15 13.91 15.8 18.7 15.8 18.7 22.5 20.61 22.5"/><polyline class="cls-1" points="13.91 8.15 18.7 8.15 18.7 0.5"/><polyline class="cls-1" points="10.09 8.15 5.3 8.15 5.3 0.5"/></svg>
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