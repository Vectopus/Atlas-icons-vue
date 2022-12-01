
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="0.5" y1="12" x2="2.42" y2="12"/><line class="cls-1" x1="6.25" y1="13.92" x2="17.75" y2="13.92"/><line class="cls-1" x1="6.25" y1="10.08" x2="17.75" y2="10.08"/><line class="cls-1" x1="21.58" y1="12" x2="23.5" y2="12"/><rect class="cls-1" x="2.42" y="5.29" width="4.79" height="13.42" rx="2.14"/><rect class="cls-1" x="16.79" y="5.29" width="4.79" height="13.42" rx="2.14"/></svg>
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