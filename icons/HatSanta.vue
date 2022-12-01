
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="20.11" cy="20.11" r="2.39"/><path class="cls-1" d="M21.55,18.68V9.14A7.64,7.64,0,0,0,13.91,1.5h0A11.46,11.46,0,0,0,2.45,13v2.87H17.73V9.14"/><path class="cls-1" d="M3.41,15.82H17.73a0,0,0,0,1,0,0v4.77a0,0,0,0,1,0,0H3.41A1.91,1.91,0,0,1,1.5,18.68v-1a1.91,1.91,0,0,1,1.91-1.91Z"/></svg>
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