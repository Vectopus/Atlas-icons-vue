
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="3.41" width="21" height="17.18"/><path class="cls-1" d="M11.05,15.82H9.14a1.91,1.91,0,0,1-1.91-1.91V10.09A1.91,1.91,0,0,1,9.14,8.18h1.91"/><path class="cls-1" d="M17.73,15.82H15.82a1.91,1.91,0,0,1-1.91-1.91V10.09a1.91,1.91,0,0,1,1.91-1.91h1.91"/></svg>
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