<script>
  import { onMount } from "svelte";

  let canvas;

  onMount(() => {
    // Code to initialize and interact with the canvas
  });
</script>

<canvas bind:this={canvas} />

<style>
  canvas {
    border: 1px solid #000;
  }
</style>
