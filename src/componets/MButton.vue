<script setup>
const props = defineProps({
    texto : String
})
</script>
<template>
    <span>Texto:</span>
    <button>{{ props.texto }}</button>
</template>

<style scoped>

button{
    background-color: blue;
    color: white ;
    font-size: 1.1 rem;
    border: 1px solid #ccc;
    border-radius: 5px;
    padding: 5px 10px;
    cursor: pointer;
}
button:hover{
    background-color: darkblue;
}

</style>