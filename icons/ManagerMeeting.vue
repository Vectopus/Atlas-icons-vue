
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M16.79,23.52a2.87,2.87,0,0,1,2.88-2.87h0a2.87,2.87,0,0,1,2.87,2.87"/><circle class="cls-1" cx="19.67" cy="16.81" r="1.92"/><path class="cls-1" d="M9.12,23.52A2.87,2.87,0,0,1,12,20.65h0a2.87,2.87,0,0,1,2.88,2.87"/><circle class="cls-1" cx="12" cy="16.81" r="1.92"/><path class="cls-1" d="M9.12,10.1A2.88,2.88,0,0,1,12,7.23h0a2.88,2.88,0,0,1,2.88,2.87"/><circle class="cls-1" cx="12" cy="3.4" r="1.92"/><path class="cls-1" d="M1.46,23.52a2.87,2.87,0,0,1,2.87-2.87h0a2.87,2.87,0,0,1,2.88,2.87"/><circle class="cls-1" cx="4.33" cy="16.81" r="1.92"/><line class="cls-1" x1="0.5" y1="11.06" x2="23.5" y2="11.06"/></svg>
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