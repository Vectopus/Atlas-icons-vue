
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M20.55,8.18v10.5H7.18L2.05,13.55a2,2,0,0,1,2.86-2.87l.64.65a1,1,0,0,0,1.63-.68V8.46a6.9,6.9,0,0,1,6.9-7,6.7,6.7,0,0,1,6.47,6.68Z"/><rect class="cls-1" x="7.18" y="18.68" width="13.36" height="3.82"/></svg>
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