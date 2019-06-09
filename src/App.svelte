<script>
	import SvelteDragula from './svelte-dragula.svelte';

  const options = {
    removeOnSpill: true
  }
</script>

<style>
</style>

<SvelteDragula {options}>
  <div class="dragula-slot">
    <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Obcaecati illo, impedit iste nesciunt quo explicabo tempore provident, fugiat nemo incidunt repellendus facere, voluptas eaque odit soluta unde voluptatum praesentium! Qui.</p>
  </div>
  <div class="dragula-slot">
    <p>Quidem libero enim provident neque, ex omnis. Velit necessitatibus magni, voluptatum quis distinctio nesciunt vero fuga aliquid ipsum cupiditate neque excepturi, nemo sit non explicabo soluta autem, rem veniam ratione!</p>
  </div>
  <div class="dragula-slot">
    <p>Ipsam eius, iusto laborum placeat aspernatur laudantium dolorem! Perspiciatis itaque aperiam, est eum commodi, doloremque fugit dicta consequatur! Molestias vel reprehenderit, officiis corrupti, sed nostrum quod expedita qui magni? Excepturi.</p>
  </div>
</SvelteDragula>
