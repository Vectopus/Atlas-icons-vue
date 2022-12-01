
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12" cy="3.41" r="1.91"/><path class="cls-1" d="M11.05,6.27H13a1.91,1.91,0,0,1,1.91,1.91v1.91L13,22.5h-1.9L9.14,10.15v-2A1.91,1.91,0,0,1,11.05,6.27Z"/><line class="cls-1" x1="15.82" y1="22.5" x2="8.18" y2="22.5"/></svg>
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