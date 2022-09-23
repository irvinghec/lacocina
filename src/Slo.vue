<template>
    <div>
        slot
        <slot></slot>
    </div>
</template>


<script>
    export default{
        name:'Slo'
    }
</script>

<style scoped>
    :slotted(img){
        width: 395px;
        height: 295px;
    }
</style>