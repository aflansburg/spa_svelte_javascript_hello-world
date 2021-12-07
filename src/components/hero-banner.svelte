<script>
  const logo = "https://cdn.auth0.com/blog/hello-auth0/svelte-logo.svg";

  const openCodeSample = () => {
    window.open(
      "https://auth0.com/developers/hub/code-samples/spa/svelte-javascript/",
      "_blank",
      "noopener noreferrer"
    );
  };
</script>

<div class="hero-banner">
  <img class="hero-banner__logo" src={logo} alt="Svelte logo" />
  <h1 class="hero-banner__headline">Hello, Svelte World!</h1>
  <p class="hero-banner__description">
    This is a sample application that demonstrates the authentication flow for a
    Svelte app using <strong>Auth0</strong>.
  </p>

  <button on:click={openCodeSample} class="button button--secondary">
    Check out the code sample →
  </button>
</div>
