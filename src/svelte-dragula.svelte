<script>
  import { onMount } from 'svelte';
  import atoa from 'atoa';
  import dragula from 'dragula';

  import 'dragula/dist/dragula.min.css';

  export let options = {};

  onMount(async () => {
    console.log(options)
    const slots = document.querySelectorAll('.dragula-container > .dragula-slot');
    const drake = dragula(atoa(slots), options);
  })
</script>
<style>
</style>

<div class="dragula-container">
  <slot></slot>
</div>
