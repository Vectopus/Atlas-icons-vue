
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="9.14" y1="10.14" x2="9.14" y2="23.5"/><line class="cls-1" x1="14.86" y1="10.14" x2="14.86" y2="23.5"/><line class="cls-1" x1="9.14" y1="16.82" x2="14.86" y2="16.82"/><line class="cls-1" x1="9.14" y1="20.64" x2="14.86" y2="20.64"/><line class="cls-1" x1="9.14" y1="13" x2="14.86" y2="13"/><polygon class="cls-1" points="12 2.5 13.24 5.01 16.02 5.42 14.01 7.37 14.48 10.14 12 8.83 9.52 10.14 9.99 7.37 7.99 5.42 10.76 5.01 12 2.5"/></svg>
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