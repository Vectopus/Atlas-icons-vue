
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="6.25" y1="12" x2="0.5" y2="12"/><polyline class="cls-1" points="3.38 9.13 6.25 12 3.38 14.88"/><line class="cls-1" x1="17.75" y1="12" x2="23.5" y2="12"/><polyline class="cls-1" points="20.63 14.88 17.75 12 20.63 9.13"/><line class="cls-1" x1="6.25" y1="12" x2="0.5" y2="12"/><polyline class="cls-1" points="3.38 9.13 6.25 12 3.38 14.88"/><line class="cls-1" x1="17.75" y1="12" x2="23.5" y2="12"/><polyline class="cls-1" points="20.63 14.88 17.75 12 20.63 9.13"/><line class="cls-1" x1="12" y1="6.25" x2="12" y2="0.5"/><polyline class="cls-1" points="14.88 3.38 12 6.25 9.13 3.38"/><circle class="cls-1" cx="12" cy="11.04" r="1.92"/><polyline class="cls-1" points="13.92 23.5 13.92 19.67 14.88 18.71 14.88 14.88 9.13 14.88 9.13 18.71 10.08 19.67 10.08 23.5"/></svg>
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