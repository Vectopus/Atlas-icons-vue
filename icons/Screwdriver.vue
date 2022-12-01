
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M15.82,12,12,8.18l4.75-5.54A3.28,3.28,0,0,1,19.23,1.5h0A3.26,3.26,0,0,1,22.5,4.77h0a3.28,3.28,0,0,1-1.14,2.48Z"/><line class="cls-1" x1="10.57" y1="6.75" x2="17.25" y2="13.43"/><polygon class="cls-1" points="3.41 22.5 1.5 22.5 1.5 20.59 3.41 17.73 6.27 17.73 6.27 20.59 3.41 22.5"/><line class="cls-1" x1="13.91" y1="10.09" x2="6.27" y2="17.73"/></svg>
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