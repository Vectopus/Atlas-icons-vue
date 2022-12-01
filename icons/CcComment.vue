
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M11.05,13.89H9.14A1.91,1.91,0,0,1,7.23,12V8.16A1.9,1.9,0,0,1,9.14,6.25h1.91"/><path class="cls-1" d="M17.73,13.89H15.82A1.91,1.91,0,0,1,13.91,12V8.16a1.9,1.9,0,0,1,1.91-1.91h1.91"/><polygon class="cls-1" points="1.5 1.48 1.5 18.66 8.18 18.66 12 21.52 15.82 18.66 22.5 18.66 22.5 1.48 1.5 1.48"/></svg>
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