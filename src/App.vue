<template>
  <div class="fixed inset-0 overflow-y-auto safe-insets bg-white flex flex-col">
    <nav class="p-4 flex items-center justify-center space-x-4">
      <router-link :to="{ name: 'home' }" exact-active-class="text-blue-500 underline">Home</router-link>
      <router-link :to="{ name: 'about' }" exact-active-class="text-blue-500 underline">About</router-link>
    </nav>
    <div class="flex flex-1 flex-col">
      <router-view/>
    </div>
  </div>
</template>
