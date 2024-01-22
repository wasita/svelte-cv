<script>
  import PressieDetail from "../items/PressieDetail.svelte";
  export let details;
</script>

<div>
  {#each details as { preWM, postWM, year, author, description, joint, onlyTwo }}
    <PressieDetail
      {preWM}
      {author}
      {postWM}
      {year}
      {description}
      {joint}
      {onlyTwo}
    />
  {/each}
</div>
