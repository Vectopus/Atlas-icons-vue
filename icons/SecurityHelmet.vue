
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M14,2.56a8.6,8.6,0,0,1,6.59,8.35v1.91H3.41V10.91A8.57,8.57,0,0,1,10,2.56"/><rect class="cls-1" x="1.5" y="12.82" width="21" height="3.82" rx="1.91"/><polygon class="cls-1" points="14.86 12.82 9.14 12.82 10.09 1.36 13.91 1.36 14.86 12.82"/></svg>
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