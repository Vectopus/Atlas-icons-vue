
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="7.2" r="1.91"/><polyline class="cls-1" points="17.74 22.5 15.83 22.5 4.35 18.67 4.35 17.72 10.09 17.72 10.09 11.02 13.91 11.02 13.91 17.72 19.65 17.72 19.65 18.67 8.17 22.5 6.26 22.5"/><polyline class="cls-1" points="13.91 11.02 14.87 11.02 17.74 7.2 17.74 6.24 13.91 2.41 13.91 0.5"/><polyline class="cls-1" points="10.09 11.02 9.13 11.02 6.26 7.2 6.26 6.24 10.09 2.41 10.09 0.5"/></svg>
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