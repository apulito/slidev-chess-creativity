<template>
  <div class="absolute bottom-6 left-6 text-xl">
    <a
      href="https://github.com/apulito/slidev-chess-creativity"
      target="_blank"
      class="slidev-icon-btn"
      hover:bg="black op-15"
    >
      <carbon:logo-github />
    </a>
    <a href="https://albertopulito.com" 
      target="_blank" 
      class="slidev-icon-btn" 
      hover:bg="black op-15">
      <carbon:earth />
    </a>
  </div>
  <div class="absolute bottom-6 right-6 text-xl flex items-center">
    <div
      @click="$slidev.nav.prev"
      class="slidev-icon-btn"
      hover:bg="black op-15"
    >
      <carbon:arrow-left />
    </div>
    <div
      @click="$slidev.nav.next"
      class="slidev-icon-btn"
      hover:bg="black op-15"
    >
      <carbon:arrow-right />
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>
