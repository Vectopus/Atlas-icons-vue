
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="5" y1="10" x2="7" y2="10"/><line class="cls-1" x1="9" y1="10" x2="11" y2="10"/><line class="cls-1" x1="13" y1="10" x2="15" y2="10"/><line class="cls-1" x1="17" y1="10" x2="19" y2="10"/><polygon class="cls-1" points="1 5 1 15 9 15 9 19 15 15 23 15 23 5 1 5"/></svg>
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