
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M6.27,7.23A5.73,5.73,0,0,1,12,1.5h0a5.73,5.73,0,0,1,5.73,5.73V22.5H6.27V14.86l5.21-3.25a5.18,5.18,0,0,0,2.43-4.38h0A1.91,1.91,0,0,0,12,5.32h0a1.91,1.91,0,0,0-1.91,1.91Z"/></svg>
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