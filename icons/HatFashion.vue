
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="1.5" y="18.68" width="21" height="3.82" rx="1.91"/><path class="cls-1" d="M13.91,3.41a1.91,1.91,0,0,1-3.82,0,1.91,1.91,0,0,1,3.82,0Z"/><line class="cls-1" x1="20.59" y1="18.68" x2="12.94" y2="5.07"/><line class="cls-1" x1="11.06" y1="5.07" x2="3.41" y2="18.68"/></svg>
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