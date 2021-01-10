<script>
  export let title;
  export let category;
  export let content;
</script>

<style>
  h2,
  p {
    margin: 0.5rem 0;
    color: black;
  }
  .Card-container {
    padding: 1em;
    border-radius: 1em;
    width: 280px;
    height: 300px;
    display: flex;
    justify-content: flex-end;
    flex-direction: column;
  }
  .SunGradient {
    background: rgb(235, 179, 127);
    background: linear-gradient(
      23deg,
      rgba(235, 179, 127, 1) 0%,
      rgba(242, 225, 184, 1) 100%
    );
  }

  .SandGradient {
    background: rgb(248, 228, 207);
    background: linear-gradient(
      90deg,
      rgba(248, 228, 207, 1) 0%,
      rgba(249, 235, 215, 1) 100%
    );
  }
  .Card-content {
    padding: 1em;
    border-radius: 1em;
  }
  .category {
    font-weight: 500;
    text-transform: uppercase;
    font-size: 0.8rem;
  }
  .container {
    margin: 0 0.5em;
  }
</style>

<li class="container">
  <div class="Card-container SunGradient">
    <div class="Card-content SandGradient">
      <span class="category">{category}</span>
      <h2>{title}</h2>
      <p>{content}</p>
    </div>
  </div>
</li>
