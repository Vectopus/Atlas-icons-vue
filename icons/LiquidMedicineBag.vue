
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="blood_bag" data-name="blood bag"><path class="cls-1" d="M4.41,1.5h15.3a0,0,0,0,1,0,0V13.93A5.74,5.74,0,0,1,14,19.67H10.15a5.74,5.74,0,0,1-5.74-5.74V1.5A0,0,0,0,1,4.41,1.5Z"/><line class="cls-1" x1="12.07" y1="23.5" x2="12.07" y2="19.67"/><path class="cls-1" d="M14.62,13.3a2.56,2.56,0,0,1-5.11,0c0-2.23,2.56-4.15,2.56-4.15S14.62,11.07,14.62,13.3Z"/><line class="cls-1" x1="19.72" y1="5.33" x2="7.28" y2="5.33"/></g></svg>
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