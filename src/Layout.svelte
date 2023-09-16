<script lang="ts">
  import Sidebar from './Sidebar.svelte';
</script>

<div class="container">
  <main>
    <slot></slot>
  </main>
  <Sidebar />
</div>

<style>
  /* Style the layout as needed */
  .container {
    display: flex;
    justify-content: flex-start;
  }

  main {
    flex-grow: 1;
    padding: 20px;
  }
</style>
