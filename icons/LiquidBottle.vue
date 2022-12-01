
<template>
    <svg :width="size" :height="size" :stroke-width="weight"  xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><g id="medical_syrup" data-name="medical syrup"><path class="cls-1" d="M8.18,5.32V7.23L5.32,10.09v10.5A1.9,1.9,0,0,0,7.23,22.5h9.54a1.9,1.9,0,0,0,1.91-1.91V10.09L15.82,7.23V5.32"/><path class="cls-1" d="M14.55,16.14a2.55,2.55,0,0,1-5.1,0C9.45,13.91,12,12,12,12S14.55,13.91,14.55,16.14Z"/><rect class="cls-1" x="7.23" y="1.5" width="9.55" height="3.82"/></g></svg>
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