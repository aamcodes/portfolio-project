<script>
  import picture from "../assets/mypic_copy.png"
</script>

<div class="home-mission">
  <div>
    <img src={picture} alt="Aaron" />
  </div>
  <div>
    <h1>I'm Aaron</h1>
    <p>I'm a Software Engineer currently working <a target="_blank" href="https://www.clover.com"  rel="noreferrer"><span>@Clover</span></a>.
    </p>
    <p>Favorite Quote: "No matter what, don't be afraid to fail and never ever ever ever give up."</p>
  </div>
</div>

<style>
  .home-mission {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 60vh;
  }

  .home-mission h1 {
    text-align: center;
  }

  .home-mission div {
    margin: 1rem;
  }

  img {
    width: 200px;
    height: 200px;
    border-radius: 1rem;
  }

  p a {
    text-decoration: none;
  }

  p span {
    color: rgb(90, 228, 90);
  }

  p {
    width: 400px;
  }
</style>