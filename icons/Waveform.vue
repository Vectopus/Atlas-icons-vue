
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="2.83" y1="8.33" x2="2.83" y2="15.67"/><line class="cls-1" x1="7.42" y1="4.67" x2="7.42" y2="19.33"/><line class="cls-1" x1="21.17" y1="8.33" x2="21.17" y2="15.67"/><line class="cls-1" x1="16.58" y1="4.67" x2="16.58" y2="19.33"/><line class="cls-1" x1="12" y1="1" x2="12" y2="23"/></svg>
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