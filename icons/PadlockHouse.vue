
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="20 8.5 20 22.5 4 22.5 4 8.5"/><polyline class="cls-1" points="23 10.5 12 1.5 1 10.5"/><rect class="cls-1" x="8" y="12.5" width="8" height="6"/><path class="cls-1" d="M12,8.5h0a2,2,0,0,1,2,2v2a0,0,0,0,1,0,0H10a0,0,0,0,1,0,0v-2A2,2,0,0,1,12,8.5Z"/></svg>
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