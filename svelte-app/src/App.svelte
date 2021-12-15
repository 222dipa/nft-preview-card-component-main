<script>
  let nftimg = "assets/images/image-equilibrium.jpg";
  let ethereumlogo = "assets/icons/icon-ethereum.svg";
  let clock = "assets/icons/icon-clock.svg";
  let avatar = "assets/images/image-avatar.png";
</script>

<div class="background">
  <div class="card">
    <div class="imgContainer">
      <img src={nftimg} class="nftimg" />
      <div class="imgoverlay" />
    </div>
    <div class="title">Equilibrium #3429</div>
    <div class="description">
      Our Equilibrium collection promotes balance and calm.
    </div>
    <div class="priceandtime">
      <div class="price">
        <img src={ethereumlogo} /><span class="ethereum">0.041 ETH</span>
      </div>
      <div class="time">
        <img src={clock} class="clockimg" /><span class="clock"
          >3 days left</span
        >
      </div>
    </div>
    <hr class="hrow" />
    <div>
      <div class="footer">
        <img src={avatar} height="33px" class="imgavatar" />
        <span class="authorCredit"
          >Creation of <a href="https://frontendmentor.io">Jules Wyvern</a
          ></span
        >
      </div>
    </div>
  </div>
</div>

<style>

  @import url("https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600&display=swap");

  * {
    font-family: "Outfit", sans-serif;
  }

  a {
    color: hsl(0, 0%, 100%);
  }

  a:hover {
    text-decoration: none;
    color: hsl(178, 100%, 50%);
  }

  .authorCredit {
    color: hsl(215, 51%, 70%);
  }

  .footer {
    display: flex;
    align-items: center;
  }

  .imgavatar {
    border: 1px solid hsl(0, 0%, 100%);
    border-radius: 100%;
    margin-right: 15px;
  }

  .hrow {
    margin-bottom: 20px;
    border: none;
    height: 1px;
    color: hsl(215, 32%, 27%);
    background-color: hsl(215, 32%, 27%);
  }
  .clockimg {
    height: min-content;
  }

  .clock {
    margin-left: 6px;
  }

  .ethereum {
    margin-left: 6px;
    font-weight: 600;
  }

  .nftimg {
    width: 100%;
    height: 100%;
    border-radius: 10px;
    background-size: cover;
  }

  .imgoverlay:hover {
    background-color: hsl(178, 100%, 50%);
    opacity: 0.5;
    cursor: pointer;
  }

  .imgoverlay {
    position: absolute;
    height: 100%;
    width: 100%;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
    transition: 0.4s ease;
    border-radius: 10px;
  }

  .time {
    display: flex;
    color: hsl(215, 51%, 70%);
    font-weight: 300;
    display: flex;
    align-items: center;
  }

  .price {
    display: flex;
    color: hsl(178, 100%, 50%);
    font-weight: 400;
  }

  .priceandtime {
    padding-bottom: 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }

  .description {
    color: hsl(0, 0%, 100%);
    font-weight: 300;
    padding-bottom: 20px;
    color: hsl(215, 51%, 70%);
    font-size: 18px;
  }

  .title:hover {
    color: hsl(178, 100%, 50%);
    cursor: pointer;
  }

  .title {
    color: hsl(0, 0%, 100%);
    font-weight: 400;
    padding-bottom: 20px;
    font-size: 22px;
  }

  .imgContainer {
    position: relative;
    max-width: 300px;
    max-height: 300px;
    border-radius: 18px;
    margin-bottom: 20px;
  }

  .card {
    background-color: hsl(216, 50%, 16%);
    max-width: 300px;
    border-radius: 18px;
    padding: 25px;
  }

  .background {
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: hsl(217, 54%, 11%);
    height: 100%;
  }

  @media only screen and (max-width: 375px) {
    .background {
      padding: 0px 20px;
    }

    * {
      font-family: "Outfit", sans-serif;
    }
  }
</style>
