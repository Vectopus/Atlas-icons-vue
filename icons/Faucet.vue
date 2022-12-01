
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M1.5,12h21a0,0,0,0,1,0,0v1a8.59,8.59,0,0,1-8.59,8.59H10.09A8.59,8.59,0,0,1,1.5,12.93V12A0,0,0,0,1,1.5,12Z"/><polyline class="cls-1" points="6.27 8.16 8.18 9.11 8.18 11.98"/><polyline class="cls-1" points="17.73 8.16 15.82 9.11 15.82 11.98"/><path class="cls-1" d="M12,12V4.34a2.86,2.86,0,0,1,2.86-2.86h0a2.86,2.86,0,0,1,2.87,2.86v1"/></svg>
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