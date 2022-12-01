
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M20.79,12A9.52,9.52,0,0,1,3.21,12a9.52,9.52,0,0,1,17.58,0Z"/><circle class="cls-1" cx="12" cy="12" r="1.95"/><line class="cls-1" x1="12" y1="2.23" x2="12" y2="8.09"/><line class="cls-1" x1="12" y1="15.91" x2="12" y2="21.77"/><line class="cls-1" x1="0.27" y1="12" x2="8.09" y2="12"/><line class="cls-1" x1="15.91" y1="12" x2="23.73" y2="12"/></svg>
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