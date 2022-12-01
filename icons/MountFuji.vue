
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M22.5,22.5h0C18.41,21.36,15.39,17,15,11.82H9C8.61,17,5.59,21.36,1.5,22.5h0"/><line class="cls-1" x1="8.18" y1="15.82" x2="12" y2="15.82"/><line class="cls-1" x1="13.91" y1="15.82" x2="15.82" y2="15.82"/><path class="cls-1" d="M6.6,14.54a7.64,7.64,0,1,1,10.8,0"/><line class="cls-1" x1="0.55" y1="22.5" x2="23.45" y2="22.5"/></svg>
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