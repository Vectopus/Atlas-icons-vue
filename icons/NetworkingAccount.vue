
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="4.33" r="2.87"/><path class="cls-1" d="M16.79,13.92h0A4.79,4.79,0,0,0,12,9.12h0a4.79,4.79,0,0,0-4.79,4.8h0"/><rect class="cls-1" x="11.04" y="20.63" width="1.92" height="1.92"/><line class="cls-1" x1="23.5" y1="21.58" x2="0.5" y2="21.58"/><line class="cls-1" x1="12" y1="14.88" x2="12" y2="21.58"/></svg>
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