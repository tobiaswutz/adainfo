<script lang="ts">
  import Select from "../../lib/components/Select.svelte";
  let current: number = 1;

</script>


<div class="bg-red-500 p-12">

  <Select bind:current choices={[1, 1, 1]} />
</div>