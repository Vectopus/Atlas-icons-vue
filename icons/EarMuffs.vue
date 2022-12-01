
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M22.5,18.2a2.37,2.37,0,0,0-1-1.94,2.12,2.12,0,0,0,.06-.44,1.91,1.91,0,1,0-3.45,1.12,2.35,2.35,0,0,0,0,2.53,1.91,1.91,0,1,0,3.45,1.12,2.12,2.12,0,0,0-.06-.44A2.38,2.38,0,0,0,22.5,18.2Z"/><path class="cls-1" d="M1.5,18.2a2.37,2.37,0,0,1,1-1.94,2.12,2.12,0,0,1-.06-.44A1.91,1.91,0,1,1,5.9,16.94a2.35,2.35,0,0,1,0,2.53,1.91,1.91,0,1,1-3.45,1.12,2.12,2.12,0,0,1,.06-.44A2.38,2.38,0,0,1,1.5,18.2Z"/><path class="cls-1" d="M4.36,13.91V9.14A7.64,7.64,0,0,1,12,1.5h0a7.64,7.64,0,0,1,7.64,7.64v4.77"/></svg>
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