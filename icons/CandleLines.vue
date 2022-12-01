
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M13.91,5.32a1.91,1.91,0,0,1-3.82,0C10.09,3.41,12,1.5,12,1.5S13.91,3.41,13.91,5.32Z"/><line class="cls-1" x1="12" y1="7.23" x2="12" y2="10.09"/><rect class="cls-1" x="7.23" y="10.09" width="9.55" height="12.41"/><line class="cls-1" x1="4.36" y1="22.5" x2="19.64" y2="22.5"/><line class="cls-1" x1="7.23" y1="12.95" x2="16.77" y2="14.86"/><line class="cls-1" x1="7.23" y1="17.73" x2="16.77" y2="19.64"/></svg>
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