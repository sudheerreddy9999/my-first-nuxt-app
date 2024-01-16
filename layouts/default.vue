<template> 
    <main>
        <nav class="flex bg-slate-400">   
            <NuxtLink to="/"  class="ml-10">Home</NuxtLink>
            <NuxtLink to="/user" class="ml-10">user</NuxtLink>
            <NuxtLink to="/profile" class="ml-10">Profile</NuxtLink>
        </nav>
        <slot/>
    </main>
</template>