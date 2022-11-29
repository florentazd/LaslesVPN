<script>
  export let title = null;
  export let list = [];
</script>

<div class="footer-line">
  <li>{title}</li>
  <ul>
    {#each list as element, id (id)}
      <li><a href={element.link}>{element.title}</a></li>
    {/each}
  </ul>
</div>
