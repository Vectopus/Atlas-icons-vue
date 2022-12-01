
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="10.09" y1="9.15" x2="10.09" y2="12.02"/><path class="cls-1" d="M10.09,5.33H12a1.91,1.91,0,0,1,1.91,1.91v0A1.91,1.91,0,0,1,12,9.15H10.09a0,0,0,0,1,0,0V5.33A0,0,0,0,1,10.09,5.33Z"/><rect class="cls-1" x="5.3" y="1.5" width="13.39" height="13.39" rx="1.91"/><line class="cls-1" x1="12" y1="14.89" x2="12" y2="23.5"/></svg>
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