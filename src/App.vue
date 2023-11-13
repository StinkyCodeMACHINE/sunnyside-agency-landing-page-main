<script setup>
function openMenu() {
  const navOptions = document.querySelector(".header__top-part__nav-options");
  const menuIcon = document.querySelector(".header__top-part__menu-icon");

  navOptions.classList.toggle("menu-opened");
  menuIcon.classList.toggle("menu-opened");
}
</script>

<template>
  <header class="header">
    <div class="header__top-part">
      <img
        class="header__top-part__logo"
        src="/assets/logo.svg"
        alt="sunnyside logo"
      />
      <nav class="header__top-part__nav-options" @click="openMenu()">
        <div class="header__top-part__nav-options__option">About</div>
        <div class="header__top-part__nav-options__option">Services</div>
        <div class="header__top-part__nav-options__option">Projects</div>
        <div class="header__top-part__nav-options__option">Contact</div>
      </nav>
      <img
        @click="openMenu()"
        class="header__top-part__menu-icon"
        src="/assets/icon-hamburger.svg"
        alt="menu icon"
      />
    </div>
    <h1 class="header__heading">WE ARE CREATIVES</h1>
    <img
      class="header__arrow-down"
      src="/assets/icon-arrow-down.svg"
      alt="arrow down"
    />
  </header>
  <main class="main">
    <div class="main__side-info">
      <div class="main__side-info__container">
        <div>
          <h2>Transform your brand</h2>
          <p>
            We are a full-service creative agency specializing in helping brands
            grow fast. Engage your clients through compelling visuals that do
            most of the marketing for you.
          </p>
          <div class="main__side-info__container__learn-more yellow">
            LEARN MORE
          </div>
        </div>
      </div>
      <div class="main__side-info__container egg"></div>
      <div class="main__side-info__container cup"></div>
      <div class="main__side-info__container">
        <div>
          <h2>Stand out to the right audience</h2>
          <p>
            Using a collaborative formula of designers, researchers,
            photographers, videographers, and copywriters, we'll build and
            extend your brand in digital places.
          </p>
          <div class="main__side-info__container__learn-more pink">
            LEARN MORE
          </div>
        </div>
      </div>
      <div class="main__side-info__combocontainer cherry">
        <div>
          <h2>Graphic Design</h2>
          <p>
            Great design makes you memorable. We deliver artwork that
            underscores your brand message and captures potential clients'
            attention.
          </p>
        </div>
      </div>
      <div class="main__side-info__combocontainer orange">
        <div>
          <h2>Photography</h2>
          <p>
            Increase your credibility by getting the most stunning, high-quality
            photos that improve your business image.
          </p>
        </div>
      </div>
    </div>
    <div class="main__reviews">
      <h2>CLIENT TESTIMONIALS</h2>
      <div class="main__reviews__container">
        <div class="main__reviews__container__review-piece">
          <img src="/assets/image-emily.jpg" alt="face pic" />
          <p>
            We put our trust in Sunnyside and they delivered, making sure our
            needs were met and deadlines were always hit.
          </p>
          <div class="main__reviews__container__review-piece__name-and-role">
            Emily R. <span>Marketing Director</span>
          </div>
        </div>
        <div class="main__reviews__container__review-piece">
          <img src="/assets/image-thomas.jpg" alt="face pic" />
          <p>
            Sunnyside's enthusiasm coupled with their keen interest in our
            brand's success made it a satisfying and enjoyable experience.
          </p>
          <div class="main__reviews__container__review-piece__name-and-role">
            Thomas S. <span>Chief Operating Officer</span>
          </div>
        </div>
        <div class="main__reviews__container__review-piece">
          <img src="/assets/image-jennie.jpg" alt="face pic" />
          <p>
            Incredible end result! Our sales increased over 400% when we worked
            with Sunnyside. Highly recommended!
          </p>
          <div class="main__reviews__container__review-piece__name-and-role">
            Jennie F. <span>Business Owner</span>
          </div>
        </div>
      </div>
    </div>
    <div class="main__bottom-pics">
      <img
        src="/assets/desktop/image-gallery-milkbottles.jpg"
        alt="some rando pic"
      />
      <img
        src="/assets/desktop/image-gallery-orange.jpg"
        alt="some rando pic"
      />
      <img src="/assets/desktop/image-gallery-cone.jpg" alt="some rando pic" />
      <img
        src="/assets/desktop/image-gallery-sugarcubes.jpg"
        alt="some rando pic"
      />
    </div>
  </main>
  <footer class="footer">
    <img class="footer__logo" src="/assets/logo.svg" alt="sunnyside log" />
    <div class="footer__nav-options">
      <div>About</div>
      <div>Services</div>
      <div>Projects</div>
    </div>
    <div class="footer__media-icons">
      <img src="/assets/icon-facebook.svg" alt="facebook icon" />
      <img src="/assets/icon-instagram.svg" alt="instagram icon" />
      <img src="/assets/icon-twitter.svg" alt="twitter icon" />
      <img src="/assets/icon-pinterest.svg" alt="pinterest icon" />
    </div>
  </footer>
</template>

<style scoped></style>
