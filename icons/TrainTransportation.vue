
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M16.35,21.58a10.5,10.5,0,1,0-8.7,0"/><path class="cls-1" d="M9.14,6.3h5.73A1.91,1.91,0,0,1,16.77,8.2v6.68a0,0,0,0,1,0,0H7.23a0,0,0,0,1,0,0V8.2A1.91,1.91,0,0,1,9.14,6.3Z"/><line class="cls-1" x1="7.23" y1="23.48" x2="9.14" y2="14.89"/><line class="cls-1" x1="16.77" y1="23.48" x2="14.86" y2="14.89"/><line class="cls-1" x1="15.5" y1="17.75" x2="8.5" y2="17.75"/><line class="cls-1" x1="8.18" y1="21.57" x2="15.82" y2="21.57"/><line class="cls-1" x1="7.23" y1="12.02" x2="10.09" y2="12.02"/><line class="cls-1" x1="13.91" y1="12.02" x2="16.77" y2="12.02"/></svg>
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