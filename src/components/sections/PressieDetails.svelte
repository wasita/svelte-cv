<script>
  import PressieDetail from "../items/PressieDetail.svelte";
  export let details;
</script>

<div>
  {#each details as { preWM, postWM, year, author, description, joint, onlyTwo, link }}
    <PressieDetail
      {preWM}
      {author}
      {postWM}
      {year}
      {description}
      {joint}
      {onlyTwo}
      {link}
    />
  {/each}
</div>
