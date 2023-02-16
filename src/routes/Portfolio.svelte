<script>
  import {projects} from '../lib/Portfolio'
  import twitter_logo from '../assets/twitter_logo.png'
  import jounce_logo from '../assets/jounce.png'
</script>

<div class="portfolio-section">
  <h1>Portfolio</h1>
  <div class="projects">
    <div>
      <img src={twitter_logo} alt="Twidah Logo"/>
      <h2>Twidah.com</h2>
      <h3>Co-Founder</h3>
      <p>Twitter-clone, built both the Frontend and Backend application with React and Node.js.</p>

      <p>Github: (Private)</p>
      <p>Website: <a href="https://www.twidah.com" target="_blank" rel="noreferrer">www.twidah.com</a></p>
    </div>
    <div>
      <img src="https://www.underdogdevs.org/images/underdogdevs-03.png?imwidth=384" alt="Underdogs Logo" />
      <h2>UnderdogDevs.org</h2>
      <h3>Full-Stack Developer</h3>
      <p>Worked on the complete refactor of authentication across both the backend and frontend application switching the provider from Okta to Auth0.</p>
      
      <p>Github: (Private)</p>
      <p>Website: <a href="https://www.twidah.com" target="_blank" rel="noreferrer">www.underdogdevs.org</a></p>
    </div>
    <div>
      <img src={jounce_logo} alt="Jounce Logo"/>
      <h2>JounceIn.com</h2>
      <h3>Co-Founder</h3>
      <p>
        Built an educational platform with Next.JS, then Migrated to Remix.js to take advantage of nested routing. Decided to Pivot to where the consumers we are targeting are, and decided on building the mobile App with React Native.
      </p>
      
      <p>Github: (Private)</p>
      <p>Website: N/A</p>
      
    </div>
  </div>
</div>

<style>
  h1 {
    text-align: center;
  }

  .portfolio-section {
    margin-bottom: 10rem;
  }

  .projects {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
  }

  .projects div {
    width: 25%;
    border-radius: 1rem;
    border: 1px solid rgb(228, 228, 228);
    text-align: center;
    margin: 1rem;
    padding: 1rem;
  }

  .projects div:hover {
    border-color: orange
  }

  .projects div a {
    text-decoration: none;
    color: rgb(228, 228, 228);
  }

  .projects div a:hover {
    color: orange;
  }

  .projects div img {
    width: 200px;
    height: 150px;
  }

  @media screen and (max-width: 600px) {
    .projects div {
      width: 100%;
    }
  }
</style>