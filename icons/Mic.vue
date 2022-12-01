
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="12" y1="22.5" x2="12" y2="18.68"/><rect class="cls-1" x="8.18" y="1.5" width="7.64" height="13.36" rx="3.7"/><path class="cls-1" d="M19.64,11.05h0A7.64,7.64,0,0,1,12,18.68h0a7.64,7.64,0,0,1-7.64-7.63h0"/><line class="cls-1" x1="9.14" y1="22.5" x2="14.86" y2="22.5"/></svg>
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