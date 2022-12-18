<script setup>
   import Authenticated from '@/Layouts/AuthenticatedLayout.vue';

</script>
<template>
    <Authenticated>
       <template #header>
           <h2 class="font-semibold text-xl text-gray-800 leading-tight">
               Index
           </h2>
       </template>

        <div class="w-3/4 mx-auto mt-8 space-y-3">
           <h1 class="font-bold text-3xl text-gray-800">Blog Name</h1>
           <div>
               <div class="space-y-1">
                   <h2 class="font-bold text-xl text-gray-800">Title</h2>
                   <p>This is a simple body.</p>
               </div>
           </div>
        </div>

    </Authenticated>
</template>