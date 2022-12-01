
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polygon class="cls-1" points="22.5 18.68 14.86 14.86 14.86 9.14 22.5 5.32 22.5 18.68"/><line class="cls-1" x1="22.5" y1="3.41" x2="22.5" y2="20.59"/><path class="cls-1" d="M3.41,9.14H14.86a0,0,0,0,1,0,0v5.73a0,0,0,0,1,0,0H3.41A1.91,1.91,0,0,1,1.5,13V11A1.91,1.91,0,0,1,3.41,9.14Z"/><line class="cls-1" x1="11.05" y1="7.23" x2="11.05" y2="9.14"/></svg>
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