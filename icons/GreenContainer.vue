
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="4.36" y="1.5" width="15.27" height="21"/><line class="cls-1" x1="2.45" y1="1.5" x2="21.55" y2="1.5"/><line class="cls-1" x1="4.36" y1="5.32" x2="19.64" y2="5.32"/><line class="cls-1" x1="4.36" y1="18.68" x2="19.64" y2="18.68"/><line class="cls-1" x1="2.45" y1="22.5" x2="21.55" y2="22.5"/><line class="cls-1" x1="2.45" y1="12" x2="6.27" y2="12"/><line class="cls-1" x1="17.73" y1="12" x2="21.55" y2="12"/><path class="cls-1" d="M8.18,8.18h2.46a4.23,4.23,0,0,1,4.23,4.23v2.46a0,0,0,0,1,0,0H12.41a4.23,4.23,0,0,1-4.23-4.23V8.18A0,0,0,0,1,8.18,8.18Z"/><line class="cls-1" x1="16.77" y1="16.77" x2="11.05" y2="11.05"/></svg>
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