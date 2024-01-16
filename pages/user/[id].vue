
<template>
    <input v-model="userValue" class="bg-slate-200" >
    <UserGreetings/>
    <div class="flex justify-center items-center mt-32 ml-96 bg-blue-100 w-96 h-32 rounded-md">
    
    Hi I am generating dynamically user id : {{id}}
    </div>
        
</template>

<script setup>
const {id} = useRoute().params;
const userValue = ref('')
</script>