
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12,7.24h0A5.74,5.74,0,0,1,17.74,13v6.7a1.91,1.91,0,0,1-1.91,1.91H8.17a1.91,1.91,0,0,1-1.91-1.91V13A5.74,5.74,0,0,1,12,7.24Z"/><line class="cls-1" x1="9.13" y1="23.5" x2="9.13" y2="21.59"/><line class="cls-1" x1="14.87" y1="23.5" x2="14.87" y2="21.59"/><polyline class="cls-1" points="9.13 8.2 9.13 1.5 14.87 1.5 14.87 8.2"/><line class="cls-1" x1="7.22" y1="1.5" x2="16.78" y2="1.5"/><line class="cls-1" x1="9.13" y1="12.98" x2="14.87" y2="12.98"/><line class="cls-1" x1="12.96" y1="15.85" x2="12.96" y2="12.98"/></svg>
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