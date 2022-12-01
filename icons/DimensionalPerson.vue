
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="12 1.78 2.23 6.67 2.23 17.41 12 22.22 21.77 17.41 21.77 6.67 12 1.78"/><line class="cls-1" x1="12" y1="12.61" x2="12" y2="12.53"/><line class="cls-1" x1="21.77" y1="17.41" x2="17.23" y2="15.18"/><line class="cls-1" x1="6.77" y1="15.18" x2="2.23" y2="17.41"/><line class="cls-1" x1="12" y1="12.61" x2="12" y2="12.53"/><line class="cls-1" x1="12" y1="5.69" x2="12" y2="1.78"/><line class="cls-1" x1="21.77" y1="17.41" x2="17.23" y2="15.18"/><line class="cls-1" x1="6.77" y1="15.18" x2="2.23" y2="17.41"/><circle class="cls-1" cx="12" cy="9.6" r="1.95"/><path class="cls-1" d="M9.07,16.44v-1A2.93,2.93,0,0,1,12,12.53h0a2.93,2.93,0,0,1,2.93,2.93v1"/></svg>
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