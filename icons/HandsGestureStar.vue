
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M12,23.5V18a2.85,2.85,0,0,0-.84-2L8.58,13.4a1.9,1.9,0,0,0-2.7,0h0a1.88,1.88,0,0,0-.56,1.35h0a2.66,2.66,0,0,0,.79,1.9l2.07,2.08"/><path class="cls-1" d="M5.32,23.5v-.95l-3-3a2.87,2.87,0,0,1-.84-2v-7.4A1.9,1.9,0,0,1,3.41,8.23h0a1.91,1.91,0,0,1,1.91,1.91v5.72l2.86,2.87"/><path class="cls-1" d="M12,23.5V18a2.85,2.85,0,0,1,.84-2l2.58-2.58a1.9,1.9,0,0,1,2.7,0h0a1.88,1.88,0,0,1,.56,1.35h0a2.66,2.66,0,0,1-.79,1.9l-2.07,2.08"/><path class="cls-1" d="M18.68,23.5v-.95l3-3a2.87,2.87,0,0,0,.84-2v-7.4a1.9,1.9,0,0,0-1.91-1.91h0a1.91,1.91,0,0,0-1.91,1.91v5.72l-2.86,2.87"/><polygon class="cls-1" points="12 2.5 13.09 4.7 15.51 5.05 13.76 6.76 14.17 9.18 12 8.04 9.83 9.18 10.24 6.76 8.49 5.05 10.91 4.7 12 2.5"/></svg>
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