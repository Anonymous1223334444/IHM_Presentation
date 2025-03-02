<template>
  <div class="slidev-layout section bg-gradient-to-b from-purple-900 to-blue-900">
    <NavBar />
    <div class="flex h-full items-center justify-center">
      <div>
        <slot />
      </div>
    </div>
  </div>
</template>

<style>
.section h1 {
  @apply text-4xl text-orange-400 font-bold mb-4;
}
</style>