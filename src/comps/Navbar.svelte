<nav>
  <a href="#/">Home</a>
  <a href="#/bio">Bio</a>
  <a href="#/experience">Experience</a>
  <a href="#/portfolio">Portfolio</a>
</nav>
<style>

  nav {
    display: flex;
    justify-content: flex-end;
  }

  a {
    text-decoration: none;
    color: rgb(228, 228, 228);
  }

  nav a {
    padding: 1rem;
  }

  nav a:hover {
    color: orange
  }

  @media screen and (max-width: 480px) {
    nav {
      display: flex;
      justify-content: center;
    }

    nav a {
      padding: .4rem;
    }
  }
  
</style>