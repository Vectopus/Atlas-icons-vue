
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M8.18,16.77A3.82,3.82,0,0,1,12,13h0a3.82,3.82,0,0,1,3.82,3.82"/><circle class="cls-1" cx="12" cy="9.61" r="2.39"/><polyline class="cls-1" points="18.68 1.5 22.5 1.5 22.5 5.32"/><line class="cls-1" x1="17.73" y1="6.27" x2="22.5" y2="1.5"/><polyline class="cls-1" points="5.32 22.5 1.5 22.5 1.5 18.68"/><line class="cls-1" x1="6.27" y1="17.73" x2="1.5" y2="22.5"/><polyline class="cls-1" points="22.5 18.68 22.5 22.5 18.68 22.5"/><line class="cls-1" x1="17.73" y1="17.73" x2="22.5" y2="22.5"/><polyline class="cls-1" points="1.5 5.32 1.5 1.5 5.32 1.5"/><line class="cls-1" x1="6.27" y1="6.27" x2="1.5" y2="1.5"/></svg>
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