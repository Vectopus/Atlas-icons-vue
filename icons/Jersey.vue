
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M20.59,11.05V22.5H3.41V11.05c3.82,0,2.86-5.33,2.86-9.55H17.73C17.73,5.72,17.73,11.05,20.59,11.05Z"/><path class="cls-1" d="M14.86,1.5c0,3.69-1.28,6.68-2.86,6.68s-2.86-3-2.86-6.68Z"/></svg>
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