<script>
  export let description;
  export let preWM;
  export let postWM;
  export let author = `Mahaphanit, W.`;
  export let year;
  export let joint;
  export let onlyTwo;
  export let journal;
  export let link;
</script>

<div class="pressie-details detail-container">
  <div class="bottom">
    {#if description}
      {#if joint}
        <!-- joint/co-first author -->
        <div class="description">
          {preWM}
          <b>{author}</b>
          *, {postWM} ({year}). {description}
          {#if journal}
            <i>{journal}</i>
          {/if}
          {#if link}
            <a href={link} target="_blank" rel="noopener noreferrer">[PDF]</a>
          {/if}
        </div>
      {:else if onlyTwo}
        <!-- only two authors e.g. Mahaphanit, W. & Chang, L.J. -->
        <div class="description">
          <b>{author}</b>
          & {postWM} ({year}). {description}
          {#if journal}
            <i>{journal}</i>
          {/if}
          {#if link}
            <a href={link} target="_blank" rel="noopener noreferrer">[PDF]</a>
          {/if}
        </div>
      {:else if preWM}
        <!-- any others before Mahaphanit -->
        <div class="description">
          {preWM},
          <b>{author}</b>
          , {postWM} ({year}). {description}
          {#if journal}
            <i>{journal}</i>
          {/if}
          {#if link}
            <a href={link} target="_blank" rel="noopener noreferrer">[PDF]</a>
          {/if}
        </div>
      {:else if postWM}
        <!-- any othres after Mahaphanit -->
        <div class="description">
          <b>{author}</b>
          , {postWM} ({year}). {description}
          {#if journal}
            <i>{journal}</i>
          {/if}
          {#if link}
            <a href={link} target="_blank" rel="noopener noreferrer">[PDF]</a>
          {/if}
        </div>
      {:else}
        <!-- Mahaphanit only e.g. for talks -->
        <div class="description">
          <b>{author}</b>
          ({year}). {description}
          {#if journal}
            <i>{journal}</i>
          {/if}
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
