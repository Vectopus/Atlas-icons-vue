
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="14.86" cy="9.14" r="7.64"/><line class="cls-1" x1="1.5" y1="22.5" x2="9.14" y2="14.86"/><path class="cls-1" d="M12,12h3.34a1.43,1.43,0,0,0,1.43-1.43h0a1.43,1.43,0,0,0-1.43-1.43h-.95A1.44,1.44,0,0,1,13,7.7h0a1.44,1.44,0,0,1,1.44-1.43h3.34"/><line class="cls-1" x1="14.86" y1="4.36" x2="14.86" y2="6.27"/><line class="cls-1" x1="14.86" y1="12" x2="14.86" y2="13.91"/></svg>
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