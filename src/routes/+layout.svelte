<script>
  import Header from "./Header.svelte";
  import "./styles.css";
</script>

<div class="app bg-[FAF9F9]">
  <Header />

  <main class="grid gap-4">
    <slot />
  </main>

  <footer></footer>
</div>

<style>
</style>
