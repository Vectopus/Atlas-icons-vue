
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="21.58" y1="19.67" x2="23.5" y2="19.67"/><path class="cls-1" d="M10.08,19.67a2.87,2.87,0,0,1-2.87,2.87c-1.59,0-4.79-1.29-4.79-2.87s3.2-2.88,4.79-2.88A2.87,2.87,0,0,1,10.08,19.67Z"/><line class="cls-1" x1="2.42" y1="19.67" x2="0.5" y2="19.67"/><path class="cls-1" d="M13.92,19.67a2.87,2.87,0,0,1,2.87-2.88c1.59,0,4.79,1.29,4.79,2.88s-3.2,2.87-4.79,2.87A2.87,2.87,0,0,1,13.92,19.67Z"/><line class="cls-1" x1="10.08" y1="19.67" x2="13.92" y2="19.67"/><path class="cls-1" d="M12,1.46h0A10.54,10.54,0,0,1,22.54,12v1.92a0,0,0,0,1,0,0H1.46a0,0,0,0,1,0,0V12A10.54,10.54,0,0,1,12,1.46Z"/></svg>
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