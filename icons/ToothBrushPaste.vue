
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="13.92" y="1.46" width="4.79" height="3.83" transform="translate(32.63 6.75) rotate(180)"/><path class="cls-1" d="M12,22.54h8.62V20.63L19.78,7.09a1.92,1.92,0,0,0-1.91-1.8H14.76a1.92,1.92,0,0,0-1.91,1.8L12,20.62Z"/><polyline class="cls-1" points="3.38 0.5 3.38 9.13 6.25 15.83 6.25 23.5"/><rect class="cls-1" x="3.38" y="1.46" width="4.79" height="6.71"/></svg>
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