<script>
  import picture from "../assets/mypic_copy.png"
</script>

<div class="home-mission">
  <div class="picture">
    <img src={picture} alt="Aaron" />
  </div>
  <div class="intro">
    <h1>I'm Aaron</h1>
    <p>I'm a Software Engineer currently working <a target="_blank" href="https://www.clover.com"  rel="noreferrer"><span>@Clover</span></a>.
    </p>
    <p>Favorite Quote: "No matter what, don't be afraid to fail and never ever ever ever give up." — ..Someone 🤷‍♂️</p>
  </div>
</div>

<style>
  .home-mission {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 60vh;
    transform: translate(30px, 0);
  }

  .home-mission .picture {
    border-radius: 60px;
    box-shadow: 0 0 0 3px black, 0 0 0 4px white;
    height: 200px;
    overflow: hidden;
    transform: rotate(-45deg) translate(-30px, -30px);
    width: 200px;
  }

  .home-mission .intro {
    border-left: 1px solid #191919;
    padding-left: 55px;
    width: 400px;
  }

  .home-mission .intro > p {
    line-height: 1.375em;
    text-align: justify;
  }

  .home-mission h1 {
    text-align: center;
  }

  .home-mission div {
    margin: 1rem;
  }

  img {
    height: 235px;
    transform: rotate(45deg) translate(-25px, 0px);
    width: 235px;
  }

  p a {
    text-decoration: none;
  }

  p span {
    color: rgb(90, 228, 90);
  }

  @media screen and (max-width: 480px) {
    .home-mission {
      display: flex;
      flex-wrap: wrap;
      margin-top: 2rem;
    }

    img {
      border-radius: 50%;
    }

    p {
      width: 100%;
    }
  }
</style>