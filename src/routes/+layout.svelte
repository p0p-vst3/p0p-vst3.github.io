<div id="main-container">
  <slot />
</div>

<style>
  @import url("https://fonts.googleapis.com/css2?family=Inter:wght@400;600;900&display=swap");

  #main-container {
    height: 100vh;
    width: 100vw;

    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
  }

  /* global styles */
  :root {
    --black: #0d0d0d;
    --gray: #a8a8a8;
    --white: #ffffff;
    --font-family: "Inter";
    font-size: clamp(1rem, 2vw, 2.2rem);
  }

  /* css reset */
  :global(body) {
    font-family: var(--font-family);
    background-color: var(--black);
    color: var(--white);
  }
  :global(*) {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  :global(a) {
    text-decoration: none;
    color: inherit;
  }
</style>
