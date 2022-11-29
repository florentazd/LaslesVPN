<script>
  import Nav from "./lib/components/nav/nav.svelte";
  import Header from "./lib/components/header/header.svelte";
  import Pricings from "./lib/components/body/pricings/pricings.svelte";
  import Location from "./lib/components/body/location.svelte";
  import Customers from "./lib/components/body/customers/customers.svelte";
  import Subscribe from "./lib/components/body/subscribe.svelte";
  import Footer from "./lib/components/footer/footer.svelte";
</script>

<main>
  <Nav />
  <Header />
  <Pricings />
  <Location />
  <Customers />
  <Subscribe />
  <Footer />
</main>

<style>
  main {
    display: flex;
    align-items: center;
    flex-direction: column;
  }
</style>
