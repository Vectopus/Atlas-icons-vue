
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="puzzle"><path class="cls-1" d="M9.7,5.88a1.87,1.87,0,0,0-.56,1.35,1.92,1.92,0,0,0,1.91,1.91H12V12H9.14V13a1.91,1.91,0,0,1-3.82,0V12H1.5V1.5H12V5.32h-.95A1.87,1.87,0,0,0,9.7,5.88Z"/><path class="cls-1" d="M22.5,1.5V12H18.68v-.95a1.91,1.91,0,0,0-1.91-1.91,1.92,1.92,0,0,0-1.91,1.91V12H12V9.14h-.95A1.92,1.92,0,0,1,9.14,7.23a1.91,1.91,0,0,1,1.91-1.91H12V1.5Z"/><path class="cls-1" d="M14.86,16.77A1.92,1.92,0,0,1,13,18.68H12V22.5H1.5V12H5.32V13a1.91,1.91,0,0,0,3.82,0V12H12v2.86H13A1.92,1.92,0,0,1,14.86,16.77Z"/><path class="cls-1" d="M22.5,12V22.5H12V18.68H13a1.91,1.91,0,0,0,0-3.82H12V12h2.86v-.95a1.92,1.92,0,0,1,1.91-1.91,1.91,1.91,0,0,1,1.91,1.91V12Z"/></g></svg>
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