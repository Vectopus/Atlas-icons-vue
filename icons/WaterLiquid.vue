
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M18.71,14.88a6.71,6.71,0,0,1-13.42,0C5.29,9.12,12,2.42,12,2.42S18.71,9.12,18.71,14.88Z"/><path class="cls-1" d="M12,17.75a2.88,2.88,0,0,1-2.88-2.87"/><line class="cls-1" x1="21.58" y1="14.88" x2="23.5" y2="14.88"/><line class="cls-1" x1="19.67" y1="21.58" x2="21.58" y2="21.58"/><line class="cls-1" x1="19.67" y1="8.17" x2="21.58" y2="8.17"/><line class="cls-1" x1="0.5" y1="14.88" x2="2.42" y2="14.88"/><line class="cls-1" x1="2.42" y1="21.58" x2="4.33" y2="21.58"/><line class="cls-1" x1="2.42" y1="8.17" x2="4.33" y2="8.17"/></svg>
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