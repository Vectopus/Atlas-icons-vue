
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="skull"><path class="cls-1" d="M6.26,23.5h0a5.83,5.83,0,0,0-4.69-5.72l-.09,0V12A10.52,10.52,0,0,1,12,1.5h0A10.52,10.52,0,0,1,22.52,12v5.74l-.09,0a5.83,5.83,0,0,0-4.69,5.72h0"/><line class="cls-1" x1="12" y1="20.63" x2="12" y2="23.5"/><line class="cls-1" x1="9.13" y1="20.63" x2="9.13" y2="23.5"/><line class="cls-1" x1="14.87" y1="20.63" x2="14.87" y2="23.5"/><circle class="cls-1" cx="7.7" cy="12.5" r="2.39"/><circle class="cls-1" cx="16.3" cy="12.5" r="2.39"/><line class="cls-1" x1="11.04" y1="17.76" x2="12.96" y2="17.76"/></g></svg>
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