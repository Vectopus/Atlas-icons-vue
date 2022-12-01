
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="heart_healt" data-name="heart healt"><path class="cls-1" d="M3.41,13l-.33-.33A5.4,5.4,0,1,1,10.72,5L12,6.3,13.28,5a5.4,5.4,0,1,1,7.64,7.63l-.33.33L12,21.57,6.07,15.64Z"/><line class="cls-1" x1="9.14" y1="12.02" x2="14.86" y2="12.02"/><line class="cls-1" x1="12" y1="9.16" x2="12" y2="14.89"/></g></svg>
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