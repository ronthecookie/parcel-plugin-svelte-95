<script>
  import "./blobaston.png";
  export let name;
</script>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 240px;
    margin: 0 auto;
  }

  h1 {
    color: #ff3e00;
    text-transform: uppercase;
    font-size: 4em;
    font-weight: 100;
  }

  @media (min-width: 640px) {
    main {
      max-width: none;
    }
  }
</style>

<main>
  <h1>Hello {name}!</h1>
  <p>
    Visit the
    <a href="https://svelte.dev/tutorial">Svelte tutorial</a>
    to learn how to build Svelte apps.
  </p>
  <p>
    If the
    <a href="https://github.com/DeMoorJasper/parcel-plugin-svelte/issues/95">
      bug
    </a>
    happends, you shouldn't see any image below:
  </p>
  <img src="/blobaston.png" alt />
</main>
