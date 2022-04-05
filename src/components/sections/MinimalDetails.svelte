<script>
    import MinimalDetail from '../items/MinimalDetail.svelte';
    export let details;
  </script>
  
  <div>
    {#each details as { description }}
      <MinimalDetail {description} />
    {/each}
  </div>
  