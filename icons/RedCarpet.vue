
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M21.58,13.46v0Z"/><circle class="cls-1" cx="21.58" cy="3.4" r="0.96"/><path class="cls-1" d="M2.42,13.46v0Z"/><circle class="cls-1" cx="2.42" cy="3.4" r="0.96"/><polygon class="cls-1" points="21.58 21.6 2.42 21.6 8.17 12.98 15.83 12.98 21.58 21.6"/><line class="cls-1" x1="23.5" y1="21.6" x2="0.5" y2="21.6"/><path class="cls-1" d="M21.58,5.31S17.29,9.15,12,9.15,2.42,5.31,2.42,5.31"/></svg>
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