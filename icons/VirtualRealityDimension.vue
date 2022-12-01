
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="19.67 9.6 19.67 18.23 12 14.4 12 5.77 19.67 9.6"/><polygon class="cls-1" points="12 5.77 12 14.4 4.33 18.23 4.33 9.6 12 5.77"/><polygon class="cls-1" points="19.67 18.23 12 22.06 4.33 18.23 12 14.4 19.67 18.23"/><line class="cls-1" x1="0.5" y1="20.15" x2="8.17" y2="16.31"/><line class="cls-1" x1="23.5" y1="20.15" x2="15.83" y2="16.31"/><line class="cls-1" x1="12" y1="1.94" x2="12" y2="5.77"/></svg>
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