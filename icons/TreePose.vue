
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="6.24" r="1.91"/><polyline class="cls-1" points="10.09 10.06 13.91 10.06 13.91 15.8 16.78 17.72 16.78 18.67 12.96 18.67 12.96 20.59"/><polyline class="cls-1" points="8.17 22.5 10.09 22.5 10.09 10.06"/><polyline class="cls-1" points="13.91 10.06 14.87 10.06 16.78 6.24 16.78 5.28 13.91 1.46 13.91 0.5"/><polyline class="cls-1" points="10.09 10.06 9.13 10.06 7.22 6.24 7.22 5.28 10.09 1.46 10.09 0.5"/></svg>
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