
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="3.41" y="1.5" width="13.36" height="21" rx="1.91"/><line class="cls-1" x1="9.14" y1="19.64" x2="11.05" y2="19.64"/><path class="cls-1" d="M12,2.45H8.18a.94.94,0,0,1-.95-1H13A.94.94,0,0,1,12,2.45Z"/><path class="cls-2" d="M20.11,22.5l-.47-2.86a1,1,0,0,1,.79-1.12,1,1,0,0,1,1.12,1.12l-.48,2.86a.49.49,0,0,1-1,0Z"/><line class="cls-3" x1="20.59" y1="1.5" x2="20.59" y2="19.64"/></svg>
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
    .cls-1,.cls-3{fill:none;stroke:currentColor;stroke-miterlimit:10;}.cls-2{fill:currentColor;}.cls-3{stroke-linecap:round;}
</style>