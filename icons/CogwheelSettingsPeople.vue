
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M16.78,23.5a2.88,2.88,0,0,1,2.87-2.87h0a2.87,2.87,0,0,1,2.87,2.87"/><circle class="cls-1" cx="19.65" cy="16.8" r="1.91"/><path class="cls-1" d="M1.48,23.5a2.87,2.87,0,0,1,2.87-2.87h0A2.88,2.88,0,0,1,7.22,23.5"/><circle class="cls-1" cx="4.35" cy="16.8" r="1.91"/><path class="cls-1" d="M16.78,7.24a3.94,3.94,0,0,0-.07-.69l1-.94L16.25,3.13,15,3.5a4.6,4.6,0,0,0-1.19-.7l-.33-1.3H10.57l-.33,1.3a4.6,4.6,0,0,0-1.19.7l-1.3-.37L6.31,5.61l1,.94a3.94,3.94,0,0,0-.07.69,3.82,3.82,0,0,0,.07.68l-1,.95,1.44,2.48L9.05,11a4.9,4.9,0,0,0,1.19.7l.33,1.3h2.86l.33-1.3A4.9,4.9,0,0,0,15,11l1.3.37,1.44-2.48-1-.95A3.82,3.82,0,0,0,16.78,7.24Z"/><circle class="cls-1" cx="12" cy="7.24" r="0.96"/></svg>
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