
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><polyline class="cls-1" points="20 8.5 20 22.5 4 22.5 4 8.5"/><polyline class="cls-1" points="23 10.5 12 1.5 1 10.5"/><path class="cls-1" d="M12.5,12l-.5.5-.5-.5a2.12,2.12,0,0,0-3,0h0a2.12,2.12,0,0,0,0,3l.5.5,3,3,3-3,.5-.5a2.12,2.12,0,0,0,0-3h0A2.12,2.12,0,0,0,12.5,12Z"/></svg>
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