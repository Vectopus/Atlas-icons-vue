
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="18.71 20.63 5.29 20.63 3.38 16.79 20.63 16.79 18.71 20.63"/><line class="cls-1" x1="0.5" y1="16.79" x2="23.5" y2="16.79"/><path class="cls-1" d="M12,6.25h0a9.58,9.58,0,0,1,9.58,9.58v1a0,0,0,0,1,0,0H2.42a0,0,0,0,1,0,0v-1A9.58,9.58,0,0,1,12,6.25Z"/><line class="cls-1" x1="12" y1="3.37" x2="12" y2="6.25"/><line class="cls-1" x1="10.08" y1="3.38" x2="13.92" y2="3.38"/></svg>
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