
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M17.73,13H6.27a1.91,1.91,0,0,1-1.91-1.9h0a5.73,5.73,0,0,1,5.73-5.73h3.82a5.73,5.73,0,0,1,5.73,5.73h0A1.91,1.91,0,0,1,17.73,13Z"/><path class="cls-1" d="M15.82,1.5h0A3.82,3.82,0,0,0,12,5.32h0"/><path class="cls-1" d="M18.68,13c0,5.28-3,9.55-6.68,9.55S5.32,18.23,5.32,13"/></svg>
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