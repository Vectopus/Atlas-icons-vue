
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><line class="cls-1" x1="0.5" y1="20.6" x2="23.5" y2="20.6"/><line class="cls-1" x1="3.38" y1="11.98" x2="3.38" y2="20.6"/><line class="cls-1" x1="20.63" y1="11.98" x2="20.63" y2="20.6"/><path class="cls-1" d="M4.33,5.27H19.67a2.88,2.88,0,0,1,2.88,2.88V12a0,0,0,0,1,0,0H1.46a0,0,0,0,1,0,0V8.15A2.88,2.88,0,0,1,4.33,5.27Z"/><line class="cls-1" x1="7.21" y1="2.4" x2="7.21" y2="7.19"/><line class="cls-1" x1="16.79" y1="2.4" x2="16.79" y2="7.19"/></svg>
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