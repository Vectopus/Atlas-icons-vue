
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="puzzle_piece" data-name="puzzle piece"><path class="cls-1" d="M12,1.5a2.86,2.86,0,0,1,2.86,2.86v1h5.73V12h-.95a2.85,2.85,0,0,0-2,.84,2.86,2.86,0,0,0,2,4.89h.95V22.5H3.41V17.73h1a2.87,2.87,0,1,0,0-5.73h-1V5.32H9.14v-1A2.86,2.86,0,0,1,12,1.5Z"/></g></svg>
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
    .cls-1{fill:none;stroke:currentColor;stroke-linecap:square;stroke-miterlimit:10;}
</style>