
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M16.89,6.14h3.9a2,2,0,0,1,2,2v7.82a2,2,0,0,1-2,1.95H14.93l-1.42-2.12a1.81,1.81,0,0,0-3,0L9.07,17.86H3.21a2,2,0,0,1-2-1.95V8.09a2,2,0,0,1,2-1.95H16.89Z"/><circle class="cls-1" cx="6.14" cy="12" r="1.95"/><circle class="cls-1" cx="17.86" cy="12" r="1.95"/></svg>
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