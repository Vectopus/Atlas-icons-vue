
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path class="cls-1" d="M8.17,18.67h3.15a5.74,5.74,0,0,0,5.14-3.17l.32-.65"/><line class="cls-1" x1="5.67" y1="6.16" x2="4.35" y2="5.28"/><path class="cls-1" d="M4.76,7.79,2.43,12v.95L8.17,22.5h4.52a7.66,7.66,0,0,0,7-4.64l.69-1.61a2.45,2.45,0,0,0,.19-.93,2.39,2.39,0,0,0-2.38-2.39h-2.4L5.67,6.16,7.22,3.37V.5"/><circle class="cls-1" cx="19.17" cy="7.67" r="2.39"/></svg>
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