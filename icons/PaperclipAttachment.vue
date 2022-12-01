
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M14.2,21.23l6.51-8.45a6.54,6.54,0,0,0-1.19-9.17A6.3,6.3,0,0,0,10.35,4.8L3,14.29c-1.89,2.26-.4,5,1.28,6.32A4.4,4.4,0,0,0,10.44,20l7.31-9.49a2.8,2.8,0,0,0-.51-3.93h0a2.81,2.81,0,0,0-3.93.51l-6.17,8"/></svg>
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