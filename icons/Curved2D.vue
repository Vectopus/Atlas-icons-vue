
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M22.5,2.45v19.1A31,31,0,0,0,12,19.64,31,31,0,0,0,1.5,21.55V2.45A31,31,0,0,0,12,4.36,31,31,0,0,0,22.5,2.45Z"/><path class="cls-1" d="M6.27,10.09V10a1.8,1.8,0,0,1,1.8-1.8h0a2,2,0,0,1,2,2h0a2,2,0,0,1-.59,1.43L6.27,14.86v1h4.78"/><path class="cls-1" d="M13.91,8.18h1.91a1.91,1.91,0,0,1,1.91,1.91v3.82a1.91,1.91,0,0,1-1.91,1.91H13.91a0,0,0,0,1,0,0V8.18A0,0,0,0,1,13.91,8.18Z"/></svg>
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