<script>
    import PressieDetail from '../items/PressieDetail.svelte';
    export let details;
  </script>
  
  <div>
    {#each details as { preWM, postWM, year, author, description}}
      <PressieDetail {preWM} {author} {postWM} {year} {description} />
    {/each}
  </div>
  