<template>
  <div class="absolute bottom-6 left-6 text-xl">
    <a
      href="https://github.com/apulito/slidev-chess-creativity"
      target="_blank"
      class="slidev-icon-btn"
    >
      <carbon:logo-github />
    </a>
    <a href="https://albertopulito.com" target="_blank" class="slidev-icon-btn">
      <carbon:earth />
    </a>
  </div>

  <div
    @click="$slidev.nav.next"
    class="absolute bottom-6 right-6 text-xl py-1"
    hover:bg="white op-10"
  >
    <carbon:arrow-right />
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>
