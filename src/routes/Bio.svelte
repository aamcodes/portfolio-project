<script>
  import {faveBooks} from '../lib/Books'
  import {hobbies} from '../lib/Hobbies'
</script>

<div class="bio-section">
  <h1>Bio</h1>
  <p>I grew up in Washington Height's and Harlem in New York City. Graduated from Bloomtech (AKA Lambda School) and completed a Highly Fellowship at Formation with Top Tier Engineers in Big Tech companies like Meta, Google, Amazon etc. I'm very passionate about learning, Web3, and whatever passions catch my interest.</p>

  <h2>Favorite Books</h2>
  <ol>
    {#each faveBooks as {name, link}}
      <a href={link} target="_blank" rel="noreferrer">
        <li>{name}</li>
      </a>
    {/each}
  </ol>

  <h2>Interests and Hobbies</h2>
  <ul>
    {#each hobbies as {name}}
        <li>{name}</li>
    {/each}
  </ul>
</div>
<style>

  .bio-section {
    max-width: 50%;
    margin: 0 auto;
  }
 
  h1, h2 {
    text-align: center;
    font-size: 2rem;
    margin-top: 3rem;
  }

  ol a {
    text-decoration: none;
    color: rgb(228, 228, 228);
  }

  ol a:hover {
    color: orange;
  }

  @media screen and (max-width: 480px) {
    .bio-section {
      max-width: 90%;
    }
  }
</style>