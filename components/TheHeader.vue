<template>
  <div class="relative bg-gray-50 text-green-600 shadow-md">
    <div class="max-w-7xl mx-auto px-3 sm:px-5 py-4">
      <div class="flex justify-between items-center">
        <NuxtLink to="/" class="inline-flex items-center gap-2">
          <Logo />
          <span class="text-xl font-bold">No Camera</span>
        </NuxtLink>
        <nav class="flex space-x-10">
          <NuxtLink to="/about">About</NuxtLink>
        </nav>
      </div>
    </div>
  </div>
</template>
