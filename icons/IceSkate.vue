
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M.5,22.52H19.63a2.86,2.86,0,0,0,2.87-2.87h0"/><path class="cls-1" d="M12.93,10.09V3a1.54,1.54,0,0,0-1.54-1.55h0a1.56,1.56,0,0,0-.7.16l-1.25.63a1.56,1.56,0,0,1-.7.16H3.37V16.78A1.92,1.92,0,0,0,5.28,18.7H18.67a1.92,1.92,0,0,0,1.92-1.92V15.61A3.82,3.82,0,0,0,18.1,12Z"/><line class="cls-1" x1="10.07" y1="6.26" x2="12.93" y2="6.26"/><line class="cls-1" x1="10.07" y1="10.09" x2="12.93" y2="10.09"/><path class="cls-1" d="M3.37,13h1a4.78,4.78,0,0,1,4.78,4.78v1"/><line class="cls-1" x1="16.76" y1="18.7" x2="16.76" y2="22.52"/><line class="cls-1" x1="7.2" y1="18.7" x2="7.2" y2="22.52"/></svg>
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