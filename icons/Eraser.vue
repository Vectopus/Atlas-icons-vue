
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M13.59,19l-2.82,2.83a2.33,2.33,0,0,1-1.63.67h0a2.31,2.31,0,0,1-1.63-.67L2.17,16.49a2.31,2.31,0,0,1-.67-1.63h0a2.33,2.33,0,0,1,.67-1.63L5,10.41Z"/><rect class="cls-1" x="7.45" y="4.17" width="12.59" height="12.15" transform="translate(-3.22 12.73) rotate(-45)"/></svg>
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