
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="eye"><path class="cls-1" d="M22.5,12A12.24,12.24,0,0,1,12,17.73,12.24,12.24,0,0,1,1.5,12,12.24,12.24,0,0,1,12,6.27,12.24,12.24,0,0,1,22.5,12Z"/><circle class="cls-1" cx="12" cy="12" r="5.73"/><circle class="cls-1" cx="12" cy="12" r="1.91"/></g></svg>
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