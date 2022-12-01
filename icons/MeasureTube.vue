
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M14.86,1.5H7.23V20.59A1.9,1.9,0,0,0,9.14,22.5H13a1.9,1.9,0,0,0,1.91-1.91V5.32l1.91-2.87v-1Z"/><line class="cls-1" x1="7.23" y1="18.68" x2="9.14" y2="18.68"/><line class="cls-1" x1="7.23" y1="14.86" x2="10.09" y2="14.86"/><line class="cls-1" x1="7.23" y1="11.05" x2="9.14" y2="11.05"/><line class="cls-1" x1="7.23" y1="7.23" x2="10.09" y2="7.23"/></svg>
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