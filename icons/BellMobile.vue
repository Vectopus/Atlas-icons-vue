
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  id="Layer_1" data-name="Layer 1" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><rect class="cls-1" x="4.36" y="1.5" width="15.27" height="21" rx="2.04"/><path class="cls-1" d="M13.91,2.45H10.09a.94.94,0,0,1-.95-1h5.72A.94.94,0,0,1,13.91,2.45Z"/><path class="cls-1" d="M12,9.14h0A2.86,2.86,0,0,1,14.86,12v2.86a0,0,0,0,1,0,0H9.14a0,0,0,0,1,0,0V12A2.86,2.86,0,0,1,12,9.14Z"/><line class="cls-1" x1="12" y1="7.23" x2="12" y2="9.14"/><line class="cls-1" x1="16.77" y1="14.86" x2="7.23" y2="14.86"/><circle class="cls-1" cx="12" cy="15.82" r="0.95"/></svg>
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