
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M20.48,10a2.82,2.82,0,0,0-.84,2,2.86,2.86,0,0,0,2.86,2.86v4.78H1.5V14.86a2.82,2.82,0,0,0,2-.84,2.85,2.85,0,0,0,0-4,2.82,2.82,0,0,0-2-.84V4.36h21V9.14A2.82,2.82,0,0,0,20.48,10Z"/><rect class="cls-1" x="13.91" y="8.18" width="1.91"/><rect class="cls-1" x="13.91" y="12" width="1.91"/><rect class="cls-1" x="13.91" y="15.82" width="1.91"/></svg>
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