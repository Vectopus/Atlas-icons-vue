
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="medical_fluid" data-name="medical fluid"><path class="cls-1" d="M20,14.5a8,8,0,0,1-16,0,13.83,13.83,0,0,1,3.1-8c.28-.38.57-.74.86-1.08A27,27,0,0,1,12,1.5S20,7.5,20,14.5Z"/><line class="cls-1" x1="8" y1="14.5" x2="16" y2="14.5"/><line class="cls-1" x1="12" y1="10.5" x2="12" y2="18.5"/></g></svg>
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