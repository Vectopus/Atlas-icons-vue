
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="12" y1="0.5" x2="12" y2="2.42"/><line class="cls-1" x1="12" y1="21.58" x2="12" y2="23.5"/><line class="cls-1" x1="23.5" y1="12" x2="21.58" y2="12"/><line class="cls-1" x1="2.42" y1="12" x2="0.5" y2="12"/><line class="cls-1" x1="12" y1="0.5" x2="12" y2="2.42"/><line class="cls-1" x1="12" y1="21.58" x2="12" y2="23.5"/><line class="cls-1" x1="23.5" y1="12" x2="21.58" y2="12"/><line class="cls-1" x1="2.42" y1="12" x2="0.5" y2="12"/><line class="cls-1" x1="20.13" y1="3.87" x2="18.78" y2="5.22"/><line class="cls-1" x1="5.22" y1="18.78" x2="3.87" y2="20.13"/><line class="cls-1" x1="5.22" y1="5.22" x2="3.87" y2="3.87"/><line class="cls-1" x1="20.13" y1="3.87" x2="18.78" y2="5.22"/><line class="cls-1" x1="5.22" y1="18.78" x2="3.87" y2="20.13"/><line class="cls-1" x1="5.22" y1="5.22" x2="3.87" y2="3.87"/><path class="cls-1" d="M18.49,13.7a6.83,6.83,0,0,0,.22-1.7A6.71,6.71,0,1,0,12,18.71a6.58,6.58,0,0,0,4.13-1.44"/><path class="cls-1" d="M22.8,19.06a3.49,3.49,0,0,1-7,0c0-3.49,3.49-6.1,3.49-6.1S22.8,15.57,22.8,19.06Z"/></svg>
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