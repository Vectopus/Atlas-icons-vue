
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="5.32" y="1.5" width="13.36" height="21" rx="1.91" transform="translate(24) rotate(90)"/><path class="cls-1" d="M21.55,13.91V10.09a.94.94,0,0,1,.95-.95h0v5.72h0A.94.94,0,0,1,21.55,13.91Z"/><line class="cls-1" x1="4.36" y1="11.05" x2="4.36" y2="12.95"/></svg>
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