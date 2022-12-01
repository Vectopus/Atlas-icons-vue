
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M19.6,7.25h0A5.7,5.7,0,0,1,13.9,13H8.39l-1.14,7.6H2.5l2.85-19H13.9A5.7,5.7,0,0,1,19.6,7.25Z"/><path class="cls-1" d="M19.57,7.73A5.65,5.65,0,0,1,21.5,12a5.71,5.71,0,0,1-5.7,5.7H12.19l-.71,4.75H6.73L7,20.55"/></svg>
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