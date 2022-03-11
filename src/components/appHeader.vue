<template>
  <div class="header">
    <div class="menu-content flex sizing flex-center">
      <div class="left-content">
        <p>Vue News Search & bookmarks</p>
      </div>
      <div class="right-menu flex">
        <nav>Top News</nav>
        <nav>Bookmarks</nav>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "AppHeader",
};
</script>

<style scoped>
.header {
  background-color: var(--dark-black);
  padding: var(--sizing-padding);
  color: var(--primary-font-color);
  height: 55px;
}

.menu-content
{
    height: 100%;
    font-size: var(--font-size-h2);
}

.right-menu
{
    column-gap: var(--flex-secondary-gap);
}
</style>
