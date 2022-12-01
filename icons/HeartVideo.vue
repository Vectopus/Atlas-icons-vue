
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M14,9.14A2.6,2.6,0,0,0,12,10a2.6,2.6,0,0,0-2-.89,2.24,2.24,0,0,0-2.43,2c0,3,4.45,4.68,4.45,4.68s4.45-1.67,4.45-4.68A2.24,2.24,0,0,0,14,9.14Z"/><line class="cls-1" x1="0.55" y1="1.5" x2="23.45" y2="1.5"/><line class="cls-1" x1="1.5" y1="5.32" x2="3.41" y2="5.32"/><line class="cls-1" x1="5.32" y1="5.32" x2="7.23" y2="5.32"/><line class="cls-1" x1="9.14" y1="5.32" x2="11.05" y2="5.32"/><line class="cls-1" x1="12.95" y1="5.32" x2="14.86" y2="5.32"/><line class="cls-1" x1="16.77" y1="5.32" x2="18.68" y2="5.32"/><line class="cls-1" x1="20.59" y1="5.32" x2="22.5" y2="5.32"/><line class="cls-1" x1="23.45" y1="22.5" x2="0.55" y2="22.5"/><line class="cls-1" x1="22.5" y1="18.68" x2="20.59" y2="18.68"/><line class="cls-1" x1="18.68" y1="18.68" x2="16.77" y2="18.68"/><line class="cls-1" x1="14.86" y1="18.68" x2="12.95" y2="18.68"/><line class="cls-1" x1="11.05" y1="18.68" x2="9.14" y2="18.68"/><line class="cls-1" x1="7.23" y1="18.68" x2="5.32" y2="18.68"/><line class="cls-1" x1="3.41" y1="18.68" x2="1.5" y2="18.68"/></svg>
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