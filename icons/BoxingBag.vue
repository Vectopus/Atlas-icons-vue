
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="7.23" y="7.23" width="9.55" height="15.27" rx="1.91"/><polygon class="cls-1" points="13.91 7.23 10.09 7.23 11.04 1.5 12.96 1.5 13.91 7.23"/><line class="cls-1" x1="7.23" y1="1.5" x2="16.77" y2="1.5"/><rect class="cls-1" x="7.23" y="11.05" width="9.55" height="7.64"/></svg>
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