
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="12 2.49 15.51 8.17 22 9.76 17.68 14.85 18.18 21.51 12 18.98 5.82 21.51 6.32 14.85 2 9.76 8.49 8.17 12 2.49"/><line class="cls-1" x1="12" y1="19" x2="12" y2="18.98"/><line class="cls-1" x1="12" y1="13" x2="12" y2="2.49"/><line class="cls-1" x1="18.18" y1="21.51" x2="12" y2="13"/><line class="cls-1" x1="12" y1="13" x2="5.82" y2="21.51"/><line class="cls-1" x1="22" y1="9.75" x2="12" y2="13"/><line class="cls-1" x1="12" y1="13" x2="2" y2="9.75"/></svg>
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