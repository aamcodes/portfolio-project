<script>
  import {experiences, academics} from '../lib/Experience'
</script>

<div class="experience-section">
  <h2>Experience</h2>
  <ul>
    {#each experiences as {title, company, link}}
      <li>
        <h3>{title} <a href={link} target="_blank" rel="noreferrer"><span>@{company}</span></a></h3>
      </li>
    {/each}
  </ul>

  <h2>Academics</h2>
  <ul>
    {#each academics as {school, title, link}}
      <li>
        <h3>
          <a href={link} target="_blank" rel="noreferrer">
            <span>{school}</span>
          </a>
            learning {title}
        </h3>
      </li>
    {/each}
  </ul>
</div>
<style>

  .experience-section {
    margin-bottom: 5rem;
  }

  h2 {
    text-align: center;
  }

  h3 span {
    color: orange;
  }

  h3 a {
    text-decoration: none;
  }

  h3 a:hover {
    text-decoration: underline;
    color: orange;
  }
</style>