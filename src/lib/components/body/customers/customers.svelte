<script>
  import Customer from "./customer.svelte";
  let customers = [
    {
      name: "Vizeh Robert",
      location: "Warsew, Poland",
      note: "4.5",
      text: "“Wow... I am very happy to use this VPN, it turned out to be more than my expectations and so far there have been no problems. LaslesVPN always the best”.",
      profileUrl: "",
    },
    {
      name: "Yessica Christy",
      location: "Shanxi, China",
      note: "4.5",
      text: "“I like it because I like to travel far and still can connect with high speed.”",
      profileUrl: "",
    },
    {
      name: "Yessica Christy",
      location: "Shanxi, China",
      note: "4.5",
      text: "“I like it because I like to travel far and still can connect with high speed.”",
      profileUrl: "",
    },
    {
      name: "Yessica Christy",
      location: "Shanxi, China",
      note: "4.5",
      text: "“This is very unusual for my business that currently requires a virtual private network that has high security.”",
      profileUrl: "",
    },
  ];
</script>

<section id="cusotmers">
  <h3>Trusted by Thousands of Happy Customer</h3>
  <p>
    These are the stories of our customers who have joined us with great
    pleasure when using this crazy feature.
  </p>
  <div class="customers-box">
    {#each customers as customer}
      <Customer {customer} />
    {/each}
  </div>
  <div class="directional-box">
    <span /><span /><span /><span />
    <div class="arrow-container">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        fill="none"
        viewBox="0 0 24 24"
        stroke-width="1.5"
        stroke="currentColor"
        class="w-6 h-6"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          d="M10.5 19.5L3 12m0 0l7.5-7.5M3 12h18"
        />
      </svg>
      <svg
        xmlns="http://www.w3.org/2000/svg"
        fill="none"
        viewBox="0 0 24 24"
        stroke-width="1.5"
        stroke="currentColor"
        class="w-6 h-6"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          d="M17.25 8.25L21 12m0 0l-3.75 3.75M21 12H3"
        />
      </svg>
    </div>
  </div>
</section>
