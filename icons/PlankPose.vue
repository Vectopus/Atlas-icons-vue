
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M1.5,17.73V14.86l13.06-5.6a1.68,1.68,0,0,1,.63-.12h0a1.58,1.58,0,0,1,1.58,1.58v6h3.82"/><line class="cls-1" x1="16.77" y1="11.59" x2="9.14" y2="14.86"/><circle class="cls-1" cx="20.59" cy="8.18" r="1.91"/></svg>
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