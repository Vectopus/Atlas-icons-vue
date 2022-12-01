
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="13.92 22.52 10.08 22.52 10.08 5.27 12 3.35 13.92 5.27 13.92 22.52"/><line class="cls-1" x1="12" y1="0.48" x2="12" y2="3.35"/><polygon class="cls-1" points="13.92 11.02 17.75 12.94 17.75 22.52 13.92 22.52 13.92 11.02"/><polygon class="cls-1" points="17.75 15.81 21.58 17.73 21.58 22.52 17.75 22.52 17.75 15.81"/><polygon class="cls-1" points="10.08 9.1 6.25 11.02 6.25 22.52 10.08 22.52 10.08 9.1"/><polygon class="cls-1" points="6.25 14.85 2.42 16.77 2.42 22.52 6.25 22.52 6.25 14.85"/><line class="cls-1" x1="0.5" y1="22.52" x2="23.5" y2="22.52"/></svg>
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