
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M18.72,17.74H10.65A2.45,2.45,0,0,1,8.2,15.28h0a2.47,2.47,0,0,1,1.16-2.09L20.63,6.26h1V17.74H23.5"/><path class="cls-1" d="M11.07,15.83,15,13.22a2.87,2.87,0,0,0,1.13-3.3l-.26-.79"/><circle class="cls-1" cx="3.89" cy="15.35" r="2.39"/></svg>
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