
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><circle class="cls-1" cx="12.02" cy="7.24" r="5.74"/><path class="cls-1" d="M2.46,23.5V21.59a9.55,9.55,0,0,1,7-9.21"/><path class="cls-1" d="M16.8,14.89l-1,1.91H9.15L7.24,18.72l1.91,1.91h6.7l1,1.91h2.87a2.86,2.86,0,0,0,2.87-2.87V17.76a2.87,2.87,0,0,0-2.87-2.87Z"/><line class="cls-1" x1="12.02" y1="18.72" x2="12.02" y2="20.63"/><line class="cls-1" x1="19.67" y1="17.76" x2="19.67" y2="19.67"/></svg>
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