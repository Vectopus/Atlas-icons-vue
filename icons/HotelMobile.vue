
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="5.32" y="1.5" width="13.36" height="21" rx="1.91"/><line class="cls-1" x1="11.05" y1="18.68" x2="12.95" y2="18.68"/><path class="cls-1" d="M13.91,2.45H10.09a.94.94,0,0,1-.95-1h5.72A.94.94,0,0,1,13.91,2.45Z"/><line class="cls-1" x1="9.14" y1="6.27" x2="9.14" y2="13.91"/><line class="cls-1" x1="14.86" y1="6.27" x2="14.86" y2="13.91"/><line class="cls-1" x1="9.14" y1="10.09" x2="14.86" y2="10.09"/></svg>
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