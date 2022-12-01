
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M15.53,7H8.47A7.24,7.24,0,0,1,2,3H22A7.24,7.24,0,0,1,15.53,7Z"/><path class="cls-1" d="M12,7v8a6,6,0,0,1-6,6H6"/><path class="cls-1" d="M12,7v8a6,6,0,0,0,6,6h0"/><line class="cls-1" x1="10" y1="14" x2="14" y2="14"/></svg>
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