
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M14.87,4.37h0a4.78,4.78,0,0,1,4.78,4.78v0a0,0,0,0,1,0,0H10.09a0,0,0,0,1,0,0v0A4.78,4.78,0,0,1,14.87,4.37Z"/><path class="cls-1" d="M14.87,4.37h0A2.87,2.87,0,0,0,12,1.5H7.22A2.86,2.86,0,0,0,4.35,4.37V23.5"/><path class="cls-1" d="M12,11.07h0Z"/><path class="cls-1" d="M15.83,11.07h0Z"/><path class="cls-1" d="M19.65,11.07h0Z"/><path class="cls-1" d="M12,14.89h0Z"/><path class="cls-1" d="M15.83,14.89h0Z"/><path class="cls-1" d="M19.65,14.89h0Z"/><path class="cls-1" d="M12,18.72h0Z"/><path class="cls-1" d="M15.83,18.72h0Z"/><path class="cls-1" d="M19.65,18.72h0Z"/><path class="cls-1" d="M12,22.54h0Z"/><path class="cls-1" d="M15.83,22.54h0Z"/><path class="cls-1" d="M19.65,22.54h0Z"/></svg>
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