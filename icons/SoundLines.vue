
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="0.5" y1="21.58" x2="6.25" y2="21.58"/><line class="cls-1" x1="9.13" y1="21.58" x2="14.88" y2="21.58"/><line class="cls-1" x1="17.75" y1="21.58" x2="23.5" y2="21.58"/><line class="cls-1" x1="0.5" y1="17.75" x2="6.25" y2="17.75"/><line class="cls-1" x1="9.13" y1="17.75" x2="14.88" y2="17.75"/><line class="cls-1" x1="17.75" y1="17.75" x2="23.5" y2="17.75"/><line class="cls-1" x1="0.5" y1="13.92" x2="6.25" y2="13.92"/><line class="cls-1" x1="9.13" y1="13.92" x2="14.88" y2="13.92"/><line class="cls-1" x1="17.75" y1="13.92" x2="23.5" y2="13.92"/><line class="cls-1" x1="9.13" y1="10.08" x2="14.88" y2="10.08"/><line class="cls-1" x1="17.75" y1="10.08" x2="23.5" y2="10.08"/><line class="cls-1" x1="9.13" y1="6.25" x2="14.88" y2="6.25"/><line class="cls-1" x1="9.13" y1="2.42" x2="14.88" y2="2.42"/></svg>
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