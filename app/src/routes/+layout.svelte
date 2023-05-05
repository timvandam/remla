<nav>
  <a href="/">Home</a>
  <a href="/restaurants">Restaurants</a>
</nav>

<slot />

<style>
  nav {
    display: flex;
    justify-content: space-around;
    align-items: center;
    background-color: #333;
    color: white;
    padding: 2rem 1rem;
    margin-bottom: 2rem;
  }

  nav a {
    color: white;
    text-decoration: none;
  }

  nav a:hover {
    text-decoration: underline;
  }

  :global(body) {
    margin: 0;
    font-family: sans-serif;
  }
</style>
