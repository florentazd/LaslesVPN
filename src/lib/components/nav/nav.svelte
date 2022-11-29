<script>
  import logo from "../../../assets/images/logo.png";
</script>

<nav class="navbar fixed h-20 space-x-4">
  <div class="navbar-start">
    <div class="dropdown">
      <label tabindex="0" class="btn btn-ghost lg:hidden">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          class="h-5 w-5"
          fill="none"
          viewBox="0 0 24 24"
          stroke="currentColor"
          ><path
            stroke-linecap="round"
            stroke-linejoin="round"
            stroke-width="2"
            d="M4 6h16M4 12h8m-8 6h16"
          /></svg
        >
      </label>
      <ul
        tabindex="0"
        class="menu menu-compact dropdown-content mt-3 p-2 shadow bg-base-100 rounded-box w-52"
      >
        <li><a href="#">About</a></li>
        <li><a href="#">Features</a></li>
        <li><a href="#">Pricing</a></li>
        <li><a href="#">Testimonals</a></li>
        <li><a href="#">Help</a></li>
      </ul>
    </div>
    <div class="flex space-x-2 items-center">
      <img src={logo} height="35" width="35" alt="logo" />
      <h3 class="text-xl font-bold">LaslesVPN</h3>
    </div>
  </div>
  <div class="navbar-center  hidden lg:flex">
    <ul
      style="color: #4F5665;"
      class="menu menu-horizontal  p-5 flex space-x-5"
    >
      <li><a href="#">About</a></li>
      <li><a href="#">Features</a></li>
      <li><a href="#">Pricing</a></li>
      <li><a href="#">Testimonals</a></li>
      <li><a href="#">Help</a></li>
    </ul>
  </div>
  <div class="navbar-end flex space-x-2">
    <button id="login" class="btn btn-link text-base"> Sign In </button>
    <button id="subscribe" class="btn btn-link text-base">Sign Up</button>
  </div>
</nav>

<style>
  nav {
    background-color: #fff;
    z-index: 10;
  }
  .navbar-center {
    margin: 0px;
  }
  .navbar-center ul {
    /* width: 100%; */
  }
  #login {
  }

  #subscribe {
    border: 1px solid #f53855;
    color: #f53855;
    width: fit-content;
    text-transform: none;
    text-decoration: none;
  }
  #login {
    color: #0b132a;
    text-decoration: none;
    text-transform: none;
  }
  @media screen and (min-width: 960px) {
    nav {
      /* width: 90%; */
    }
    .navbar-start {
      /* width: fit-content; */
    }
    #subscribe {
      width: 150px;
      border-radius: 50px;
    }
    #subscribe,
    #login {
      padding: 10px 20px;
    }
  }
  @media screen and (max-width: 960px) {
    #subscribe,
    #login {
      padding: 10px;
    }
  }
  .navbar-center li a:hover {
    background-color: inherit;
  }
  .navbar-center li a:focus {
    background-color: inherit;
    text-decoration: underline;
  }
</style>
