
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M21.58,12v5.75H17.75V13a2.87,2.87,0,0,0-2.87-2.88H9.12A2.87,2.87,0,0,0,6.25,13v4.79H2.42V12A5.75,5.75,0,0,1,8.17,6.25h7.66A5.75,5.75,0,0,1,21.58,12Z"/><line class="cls-1" x1="0.5" y1="17.75" x2="8.17" y2="17.75"/><line class="cls-1" x1="15.83" y1="17.75" x2="23.5" y2="17.75"/></svg>
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