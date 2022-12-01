
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12,1.5h0a5.73,5.73,0,0,1,5.73,5.73V22.5a0,0,0,0,1,0,0H6.27a0,0,0,0,1,0,0V7.23A5.73,5.73,0,0,1,12,1.5Z"/><circle class="cls-1" cx="12" cy="7.23" r="5.73"/><polyline class="cls-1" points="14.86 7.23 12 7.23 12 3.41"/><circle class="cls-1" cx="12" cy="17.73" r="0.95"/><line class="cls-1" x1="12" y1="12.95" x2="12" y2="16.77"/><line class="cls-1" x1="20.59" y1="22.5" x2="3.41" y2="22.5"/></svg>
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