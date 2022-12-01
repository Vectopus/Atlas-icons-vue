
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="1.5" width="21" height="16.23"/><line class="cls-1" x1="12" y1="22.5" x2="12" y2="17.73"/><line class="cls-1" x1="16.77" y1="22.5" x2="7.23" y2="22.5"/><path class="cls-1" d="M9.14,7.23H11a0,0,0,0,1,0,0V11a0,0,0,0,1,0,0H9.14A1.91,1.91,0,0,1,7.23,9.14v0A1.91,1.91,0,0,1,9.14,7.23Z"/><polygon class="cls-1" points="11.04 7.23 15.82 5.32 15.82 12.96 11.04 11.04 11.04 7.23"/><line class="cls-1" x1="11.05" y1="14.86" x2="9.14" y2="11.05"/></svg>
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