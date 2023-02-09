
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M3.41,17.74H1.5v-1L7.34,7.6A2.92,2.92,0,0,1,9.79,6.26h0a2.91,2.91,0,0,1,2.14.94l9.66,10.54H23.5"/><line class="cls-1" x1="11.77" y1="12.25" x2="7.42" y2="7.5"/><circle class="cls-1" cx="15.37" cy="14.39" r="2.39"/></svg>
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