
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M20.8,19.61a10.34,10.34,0,0,0,1.7-5.72,10.5,10.5,0,0,0-21,0,10.34,10.34,0,0,0,1.7,5.72"/><circle class="cls-1" cx="12" cy="13.89" r="5.73"/><line class="cls-1" x1="11.05" y1="12.93" x2="7.95" y2="9.84"/></svg>
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