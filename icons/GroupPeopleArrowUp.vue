
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M16.77,23.5a2.86,2.86,0,0,1,2.87-2.86h0A2.86,2.86,0,0,1,22.5,23.5"/><circle class="cls-1" cx="19.64" cy="16.82" r="1.91"/><path class="cls-1" d="M9.14,23.5A2.86,2.86,0,0,1,12,20.64h0a2.86,2.86,0,0,1,2.86,2.86"/><circle class="cls-1" cx="12" cy="16.82" r="1.91"/><path class="cls-1" d="M1.5,23.5a2.86,2.86,0,0,1,2.86-2.86h0A2.86,2.86,0,0,1,7.23,23.5"/><circle class="cls-1" cx="4.36" cy="16.82" r="1.91"/><polyline class="cls-1" points="14.86 13.96 14.86 9.18 17.73 9.18 12 2.5 6.27 9.18 9.14 9.18 9.14 13.96"/></svg>
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