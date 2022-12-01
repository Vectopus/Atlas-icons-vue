
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="3.38" y="3.38" width="17.25" height="17.25" rx="2.18"/><rect class="cls-1" x="7.21" y="7.21" width="9.58" height="9.58" rx="1.92"/><line class="cls-1" x1="7.21" y1="0.5" x2="7.21" y2="2.42"/><line class="cls-1" x1="12" y1="0.5" x2="12" y2="2.42"/><line class="cls-1" x1="16.79" y1="0.5" x2="16.79" y2="2.42"/><line class="cls-1" x1="7.21" y1="21.58" x2="7.21" y2="23.5"/><line class="cls-1" x1="12" y1="21.58" x2="12" y2="23.5"/><line class="cls-1" x1="16.79" y1="21.58" x2="16.79" y2="23.5"/><line class="cls-1" x1="0.5" y1="16.79" x2="2.42" y2="16.79"/><line class="cls-1" x1="0.5" y1="12" x2="2.42" y2="12"/><line class="cls-1" x1="0.5" y1="7.21" x2="2.42" y2="7.21"/><line class="cls-1" x1="21.58" y1="16.79" x2="23.5" y2="16.79"/><line class="cls-1" x1="21.58" y1="12" x2="23.5" y2="12"/><line class="cls-1" x1="21.58" y1="7.21" x2="23.5" y2="7.21"/></svg>
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