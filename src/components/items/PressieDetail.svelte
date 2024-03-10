<script>
  export let description;
  export let author = "Mahaphanit, W.";
  export let preWM;
  export let postWM;
  export let year;
  export let joint;
  export let onlyTwo;
  export let link;
</script>

<div class="pressie-details detail-container">
  <div class="bottom">
    {#if description}
      {#if joint}
        <div class="description">
          {preWM}
          <b>{author}*</b>
          , {postWM} ({year}). {description}
          {#if link}
            <a href={link} target="_blank" rel="noopener noreferrer">[PDF]</a>
          {/if}
        </div>
      {:else if onlyTwo}
        <div class="description">
          <b>{author}</b>
          & {postWM} ({year}). {description}
          {#if link}
            <a href={link} target="_blank" rel="noopener noreferrer">[PDF]</a>
          {/if}
        </div>
      {:else if preWM}
        <div class="description">
          {preWM},
          <b>{author}</b>
          , {postWM} ({year}). {description}
          {#if link}
            <a href={link} target="_blank" rel="noopener noreferrer">[PDF]</a>
          {/if}
        </div>
      {:else if postWM}
        <div class="description">
          <b>{author}</b>
          , {postWM} ({year}). {description}
          {#if link}
            <a href={link} target="_blank" rel="noopener noreferrer">[PDF]</a>
          {/if}
        </div>
      {:else}
        <div class="description">
          <b>{author}</b>
          ({year}). {description}
          {#if link}
            <a href={link} target="_blank" rel="noopener noreferrer">[PDF]</a>
          {/if}
        </div>
      {/if}
    {/if}
  </div>
</div>

<style>
  .pressie-details:last-child {
    margin-bottom: 6px;
  }
</style>
