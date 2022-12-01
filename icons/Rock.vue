
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M11.05,12A1.91,1.91,0,0,1,13,10.11h0A1.91,1.91,0,0,1,14.86,12"/><path class="cls-1" d="M14.86,12a1.92,1.92,0,0,1,1.91-1.91h0A1.91,1.91,0,0,1,18.68,12"/><path class="cls-1" d="M18.68,12V5.34a1.92,1.92,0,0,1,1.91-1.91h0A1.91,1.91,0,0,1,22.5,5.34v9.55a9.87,9.87,0,0,1-.71,3.68L21.3,19.8a9.87,9.87,0,0,0-.71,3.68h0"/><path class="cls-1" d="M8.18,23.48h0a4.57,4.57,0,0,0-1.35-3.26L2.09,15.48a2,2,0,0,1-.59-1.43,2.07,2.07,0,0,1,.59-1.44,2,2,0,0,1,2.87,0l2.27,2.28V3.43A1.91,1.91,0,0,1,9.14,1.52h0a1.92,1.92,0,0,1,1.91,1.91V12"/></svg>
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