
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="12" y1="0.5" x2="12" y2="2.42"/><line class="cls-1" x1="23.5" y1="12" x2="21.58" y2="12"/><line class="cls-1" x1="2.42" y1="12" x2="0.5" y2="12"/><line class="cls-1" x1="12" y1="0.5" x2="12" y2="2.42"/><line class="cls-1" x1="23.5" y1="12" x2="21.58" y2="12"/><line class="cls-1" x1="2.42" y1="12" x2="0.5" y2="12"/><line class="cls-1" x1="20.13" y1="3.87" x2="18.78" y2="5.22"/><line class="cls-1" x1="5.22" y1="5.22" x2="3.87" y2="3.87"/><line class="cls-1" x1="20.13" y1="3.87" x2="18.78" y2="5.22"/><line class="cls-1" x1="5.22" y1="5.22" x2="3.87" y2="3.87"/><path class="cls-1" d="M23.5,15.83h-6A6.56,6.56,0,0,0,18.71,12,6.71,6.71,0,0,0,5.29,12,6.56,6.56,0,0,0,6.5,15.83H.5"/><polyline class="cls-1" points="9.13 19.67 12 16.79 14.88 19.67"/><line class="cls-1" x1="12" y1="23.5" x2="12" y2="17.75"/></svg>
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