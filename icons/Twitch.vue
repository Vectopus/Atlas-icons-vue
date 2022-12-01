
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="3.41 1.49 22.5 1.49 22.5 13.9 16.77 19.63 12 19.63 9.61 22.01 7.23 22.01 7.23 19.63 1.5 19.63 1.5 4.35 3.41 1.49"/><polygon class="cls-1" points="5.32 4.35 19.64 4.35 19.64 12.94 15.82 16.76 11.04 16.76 10.09 17.72 10.09 16.76 5.32 16.76 5.32 4.35"/><line class="cls-1" x1="11.05" y1="7.22" x2="11.05" y2="11.99"/><line class="cls-1" x1="15.82" y1="7.22" x2="15.82" y2="11.99"/></svg>
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