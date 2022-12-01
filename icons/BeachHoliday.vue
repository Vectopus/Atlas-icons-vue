
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="0.5" y1="22.55" x2="23.5" y2="22.55"/><polyline class="cls-1" points="23.5 18.71 12 18.71 8.17 14.88"/><line class="cls-1" x1="12.96" y1="22.55" x2="12.96" y2="18.71"/><line class="cls-1" x1="20.63" y1="22.55" x2="20.63" y2="18.71"/><line class="cls-1" x1="8.22" y1="8.47" x2="3.04" y2="22.73"/><path class="cls-1" d="M9,1.81h.82A6.79,6.79,0,0,1,16.6,8.6v.08a0,0,0,0,1,0,0H2.2a0,0,0,0,1,0,0V8.6A6.79,6.79,0,0,1,9,1.81Z" transform="translate(2.36 -2.9) rotate(20)"/></svg>
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