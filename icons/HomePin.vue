
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M20,9.5c0,6-8,13-8,13s-8-7-8-13a8,8,0,0,1,16,0Z"/><polyline class="cls-1" points="14 8 14 12.5 10 12.5 10 8"/><polyline class="cls-1" points="8 9.5 12 6.5 16 9.5"/></svg>
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