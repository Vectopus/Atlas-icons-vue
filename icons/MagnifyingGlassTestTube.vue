
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M13.91,8.18V1.5H8.18v8.59l-6.29,9a2.25,2.25,0,0,0-.39,1.25h0A2.17,2.17,0,0,0,3.68,22.5H18.41"/><line class="cls-1" x1="6.27" y1="1.5" x2="15.82" y2="1.5"/><circle class="cls-1" cx="15.82" cy="13.91" r="3.82"/><line class="cls-1" x1="18.2" y1="16.3" x2="22.5" y2="20.59"/></svg>
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