
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="19.67" cy="3.38" r="1.92"/><path class="cls-1" d="M1.46,20.62a2.88,2.88,0,0,1,2.87-2.87h0a2.88,2.88,0,0,1,2.88,2.87"/><path class="cls-1" d="M16.79,10.08a2.88,2.88,0,0,1,2.88-2.87h0a2.88,2.88,0,0,1,2.87,2.87"/><circle class="cls-1" cx="12" cy="9.13" r="1.92"/><path class="cls-1" d="M9.12,15.83A2.88,2.88,0,0,1,12,13h0a2.87,2.87,0,0,1,2.87,2.87"/><circle class="cls-1" cx="4.33" cy="13.92" r="1.92"/><polyline class="cls-1" points="0.5 22.54 9.13 22.54 9.13 17.75 16.79 17.75 16.79 12 23.5 12"/></svg>
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