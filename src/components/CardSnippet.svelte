<script>
  export let category;
  export let title;
  export let content;
  export let length;
  export let type;
  export let isVideo = type === "video";
</script>

<style>
  h2,
  p {
    color: white;
    margin: 0.5em 0;
  }
  .Card {
    width: 240px;
    margin: 0 0.5em;
  }
  .top {
    background-color: #c49db9;
    height: 60px;
    position: relative;
  }
  .bottom {
    background-color: #3b4d7a;
  }
  .padding-sm {
    padding: 1em;
  }

  .borderTop {
    border-top-left-radius: 1em;
    border-top-right-radius: 1em;
  }
  .borderBottom {
    border-bottom-left-radius: 1em;
    border-bottom-right-radius: 1em;
  }
  .topIcon {
    position: absolute;
    top: 0;
    right: 0;
    padding: 1em;
    text-transform: uppercase;
    font-size: 0.8rem;
    font-weight: 500;
  }
  .bottomLabel {
    position: absolute;
    bottom: 0;
    left: 0;
    text-transform: uppercase;
    font-size: 0.8rem;
    font-weight: 500;
    padding: 1em;
  }
</style>

<li>
  <div class="Card">
    <div class="top padding-sm borderTop">
      {#if isVideo}<span class="topIcon">{length}</span>{/if}
      <span class="bottomLabel">{category}</span>
    </div>
    <div class="bottom padding-sm borderBottom">
      <h2>{title}</h2>
      <p>{content}</p>
    </div>
  </div>
</li>
