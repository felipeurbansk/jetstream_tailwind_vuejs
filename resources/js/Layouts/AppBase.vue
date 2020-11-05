<template>
  <div class="min-h-screen flex flex-col lg:flex-row">
    <nav class="w-full lg:w-1/5 bg-green-700"></nav>
    <main class="w-full lg:w-4/5">
      <slot></slot>
    </main>
  </div>
</template>

<script>
export default {};
</script>
