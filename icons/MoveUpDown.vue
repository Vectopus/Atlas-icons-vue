
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M13,22.5,7.82,17.36a2,2,0,0,1-.59-1.43,2,2,0,0,1,2-2,2,2,0,0,1,1.43.59L12,15.82V6.38a2,2,0,0,1,1.74-2,1.87,1.87,0,0,1,1.51.56,1.83,1.83,0,0,1,.57,1.34V12l5,.72a1.91,1.91,0,0,1,1.64,1.89h0a17.18,17.18,0,0,1-1.82,7.71l-.09.18"/><polyline class="cls-1" points="7.23 11.04 4.36 13.91 1.5 11.04"/><line class="cls-1" x1="4.36" y1="6.27" x2="4.36" y2="13.91"/><polyline class="cls-1" points="5.32 4.36 8.18 1.5 11.04 4.36"/><line class="cls-1" x1="8.18" y1="9.14" x2="8.18" y2="1.5"/></svg>
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