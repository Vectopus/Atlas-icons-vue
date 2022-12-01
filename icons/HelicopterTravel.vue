
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M22.54,14.58v.88a3.2,3.2,0,0,1-3.21,3.21h-5a3.2,3.2,0,0,1-3.21-3.21V12.93L1.5,9.11v-1H16.12A6.43,6.43,0,0,1,22.54,14.58Z"/><line class="cls-1" x1="13.93" y1="18.67" x2="13.93" y2="22.5"/><line class="cls-1" x1="18.72" y1="18.67" x2="18.72" y2="22.5"/><path class="cls-1" d="M22.54,20.59h0a1.91,1.91,0,0,1-1.91,1.91H11.07"/><path class="cls-1" d="M22.54,14.58v.27H16.8a1.92,1.92,0,0,1-1.91-1.92V8.15h1.23"/><line class="cls-1" x1="1.5" y1="5.28" x2="1.5" y2="9.11"/><line class="cls-1" x1="4.37" y1="2.41" x2="23.5" y2="2.41"/><line class="cls-1" x1="13.93" y1="5.28" x2="13.93" y2="0.5"/><polygon class="cls-1" points="16.8 8.15 11.06 8.15 12.02 5.28 15.85 5.28 16.8 8.15"/></svg>
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