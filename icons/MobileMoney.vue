
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="4.36" y="1.5" width="15.27" height="21" rx="2.04"/><path class="cls-1" d="M13.91,2.45H10.09a.94.94,0,0,1-.95-1h5.72A.94.94,0,0,1,13.91,2.45Z"/><path class="cls-1" d="M9.14,14.86h3.34a1.43,1.43,0,0,0,1.43-1.43h0A1.43,1.43,0,0,0,12.48,12h-1a1.43,1.43,0,0,1-1.43-1.43h0a1.43,1.43,0,0,1,1.43-1.43h3.34"/><line class="cls-1" x1="12" y1="7.23" x2="12" y2="9.14"/><line class="cls-1" x1="12" y1="14.86" x2="12" y2="16.77"/></svg>
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