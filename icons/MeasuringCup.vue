
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M5.27,1.5H3.36v1L5.27,5.32V20.59A1.91,1.91,0,0,0,7.18,22.5h9.55a1.91,1.91,0,0,0,1.91-1.91V1.5Z"/><polyline class="cls-1" points="11 7.23 14.82 7.23 14.82 22.5 11 22.5"/><line class="cls-1" x1="11.95" y1="11.05" x2="14.82" y2="11.05"/><line class="cls-1" x1="11" y1="14.86" x2="14.82" y2="14.86"/><line class="cls-1" x1="11.95" y1="18.68" x2="14.82" y2="18.68"/></svg>
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