<script>
  import Pricing from "./pricing.svelte";
  let prices = [
    { checked: 4, amount: 0, plan: "Free" },
    { checked: 5, amount: 9, plan: "Premium" },
    { checked: 12, amount: 12, plan: "Business" },
  ];
</script>

<section id="pricings">
  <h4>Choose Your Plan</h4>
  <p>
    Let's choose the package that is best for you and explore it happily and
    cheerfully.
  </p>
  <div class="pricings-box">
    {#each prices as price}
      <Pricing {price} />
    {/each}
  </div>
</section>
