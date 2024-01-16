<template>
    <div class="flex justify-center items-center mt-32 ml-96 bg-blue-100 w-72 h-32 rounded-md">
        <h2>Hi I am from index.vue from user Folder</h2>
    </div>
</template>
<!-- pages/index.vue
<template>
    <div>
      <h1>{{ greeting }}</h1>
      <form @submit.prevent="submitName">
        <label>Enter Your Name</label>
        <input type="text" class="bg-slate-300" v-model="numberInputValue" />
        <button type="submit">Submit</button>
      </form>
    </div>
  </template>
  
  <script setup>
  import { ref } from 'vue';
  import { useRouter } from 'nuxt';

  console.log("kalyan")
  
  const numberInputValue = ref('sudheer');
  const router = useRouter();

  console.log("kalyan2")
  
  function submitName() {
    router.addRoute({ name: 'home', path: '/home', component: Home })
  }
  </script>
   -->