
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M2.45,1.5h7.64a0,0,0,0,1,0,0v8.73a3.68,3.68,0,0,1-3.68,3.68H6.13a3.68,3.68,0,0,1-3.68-3.68V1.5a0,0,0,0,1,0,0Z"/><path class="cls-1" d="M13.91,1.5h7.64a0,0,0,0,1,0,0v8.73a3.68,3.68,0,0,1-3.68,3.68h-.28a3.68,3.68,0,0,1-3.68-3.68V1.5A0,0,0,0,1,13.91,1.5Z"/><line class="cls-1" x1="6.27" y1="22.5" x2="6.27" y2="13.91"/><line class="cls-1" x1="17.73" y1="22.5" x2="17.73" y2="13.91"/><line class="cls-1" x1="2.45" y1="7.23" x2="10.09" y2="7.23"/><line class="cls-1" x1="13.91" y1="7.23" x2="21.55" y2="7.23"/><line class="cls-1" x1="2.45" y1="22.5" x2="10.09" y2="22.5"/><line class="cls-1" x1="13.91" y1="22.5" x2="21.55" y2="22.5"/></svg>
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