
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="22.5 1.48 22.5 4.03 19.45 10.07"/><path class="cls-1" d="M18.3,12l-4.84,8.07a3.05,3.05,0,0,1-2.61,1.47h0A3,3,0,0,1,8.3,20.14l-4.57-7A2,2,0,0,1,3.41,12h0a2,2,0,0,1,2-2H21.55"/><line class="cls-1" x1="13.55" y1="19.9" x2="8.18" y2="11.66"/><circle class="cls-1" cx="3.89" cy="4.82" r="2.39"/></svg>
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