
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="10.09" cy="10.09" r="8.59"/><line class="cls-1" x1="22.5" y1="22.5" x2="16.3" y2="16.3"/><path class="cls-1" d="M7.23,14.86A2.86,2.86,0,0,1,10.09,12h0A2.86,2.86,0,0,1,13,14.86"/><circle class="cls-1" cx="10.09" cy="8.18" r="1.91"/></svg>
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