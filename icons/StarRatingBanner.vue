
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="12 5 12.49 5.99 13.58 6.15 12.79 6.92 12.97 8 12 7.49 11.03 8 11.21 6.92 10.42 6.15 11.51 5.99 12 5"/><polygon class="cls-1" points="19 7 19.49 7.99 20.58 8.15 19.79 8.91 19.98 10 19 9.49 18.02 10 18.21 8.91 17.42 8.15 18.51 7.99 19 7"/><polygon class="cls-1" points="5 7 5.49 7.99 6.58 8.15 5.79 8.91 5.97 10 5 9.49 4.03 10 4.21 8.91 3.42 8.15 4.51 7.99 5 7"/><polygon class="cls-1" points="7 20 2 20 3 18 2 16 7 16 7 20"/><polygon class="cls-1" points="17 20 22 20 21 18 22 16 17 16 17 20"/><rect class="cls-1" x="7" y="14" width="10" height="4"/></svg>
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