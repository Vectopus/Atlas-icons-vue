
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="20.59" r="1.91"/><polyline class="cls-1" points="4.35 22.5 6.26 22.5 6.26 17.72 10.09 16.76 13.91 16.76 17.74 17.72 17.74 22.5 19.65 22.5"/><polyline class="cls-1" points="13.91 0.5 13.91 16.76 10.09 16.76 10.09 0.5"/></svg>
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