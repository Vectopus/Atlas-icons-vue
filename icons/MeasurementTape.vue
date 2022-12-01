
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M13.91,4.39H22.5a0,0,0,0,1,0,0V13a4.77,4.77,0,0,1-4.77,4.77H13.91A4.77,4.77,0,0,1,9.14,13V9.16a4.77,4.77,0,0,1,4.77-4.77Z" transform="translate(31.64 22.14) rotate(-180)"/><circle class="cls-1" cx="15.82" cy="11.07" r="2.86"/><line class="cls-1" x1="8.18" y1="9.16" x2="8.18" y2="13.93"/><polyline class="cls-1" points="1.5 20.61 1.5 16.8 9.14 16.8"/></svg>
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