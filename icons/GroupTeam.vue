
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="3.89" r="2.39"/><circle class="cls-1" cx="19.65" cy="5.33" r="1.91"/><circle class="cls-1" cx="4.35" cy="5.33" r="1.91"/><polyline class="cls-1" points="13.91 23.5 13.91 15.85 14.87 14.89 14.87 8.2 9.13 8.2 9.13 14.89 10.09 15.85 10.09 23.5"/><polyline class="cls-1" points="21.57 21.59 21.57 15.37 21.57 9.15 17.74 9.15 17.74 15.37 17.74 21.59"/><polyline class="cls-1" points="6.26 21.59 6.26 15.37 6.26 9.15 2.44 9.15 2.44 15.37 2.44 21.59"/></svg>
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