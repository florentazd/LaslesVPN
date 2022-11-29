<script>
  import Line from "./line.svelte";

  let links = [
    [
      { title: "Dowload", link: "http://google.com" },
      { title: "Pricing", link: "http://google.com" },
      { title: "Locations", link: "http://google.com" },
      { title: "Servers", link: "http://google.com" },
      { title: "Countries", link: "http://google.com" },
      { title: "Blog", link: "http://google.com" },
    ],
    [
      { title: "LaslesVPN", link: "http://google.com" },
      { title: "FAQ", link: "http://google.com" },
      { title: "Tutorials", link: "http://google.com" },
      { title: "About Us", link: "http://google.com" },
      { title: "Privacy policy", link: "http://google.com" },
      { title: "Terms of Service", link: "http://google.com" },
    ],
    [
      { title: "Affiliate", link: "http://google.com" },
      { title: "Become Partner", link: "http://google.com" },
    ],
  ];
  let headers = ["Product", "Engage", "Earn Money"];
</script>

<footer>
  <div class="footer-left">
    <!--  -->
  </div>
  <div class="footer-right">
    {#each links as list, id (id)}
      <Line title={headers[id]} {list} />
    {/each}
  </div>
</footer>
