<template>
  <section class="home section" id="home">
    <div class="home__container container grid">
      <div class="home__content grid">
        <div class="home__social">
          <a
            href="https://www.linkedin.com/in/mikr13"
            target="_blank"
            rel="noopener"
            class="home__social-icon"
          >
            <i class="uil uil-linkedin-alt"></i>
          </a>
          <a
            href="https://github.com/mikr13/"
            target="_blank"
            rel="noopener"
            class="home__social-icon"
          >
            <i class="uil uil-github-alt"></i>
          </a>
          <a
            href="https://twitter.com/opendevs_2020"
            target="_blank"
            rel="noopener"
            class="home__social-icon"
          >
            <i class="uil uil-twitter-alt"></i>
          </a>
        </div>

        <div class="home__img">
          <svg
            class="home__blog"
            viewBox="0 0 200 187"
            xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink"
          >
            <mask id="mask0" mask-type="alpha">
              <path
                d="M190.312 36.4879C206.582 62.1187 201.309 102.826 182.328 134.186C163.346 165.547 
        130.807 187.559 100.226 186.353C69.6454 185.297 41.0228 161.023 21.7403 129.362C2.45775 
        97.8511 -7.48481 59.1033 6.67581 34.5279C20.9871 10.1032 59.7028 -0.149132 97.9666 
        0.00163737C136.23 0.303176 174.193 10.857 190.312 36.4879Z"
              />
            </mask>
            <g mask="url(#mask0)">
              <path
                d="M190.312 36.4879C206.582 62.1187 201.309 102.826 182.328 134.186C163.346 
        165.547 130.807 187.559 100.226 186.353C69.6454 185.297 41.0228 161.023 21.7403 
        129.362C2.45775 97.8511 -7.48481 59.1033 6.67581 34.5279C20.9871 10.1032 59.7028 
        -0.149132 97.9666 0.00163737C136.23 0.303176 174.193 10.857 190.312 36.4879Z"
              />
              <image
                class="home__blob-img"
                x="12"
                y="18"
                xlink:href="../../assets/images/perfil.png"
              />
            </g>
          </svg>
        </div>

        <div class="home__data">
          <h1 class="home__title">Hi, I'm Mihir</h1>
          <h3 class="home__subtitle">Frontend developer</h3>
          <p class="home__description">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Veniam
            tempora earum nulla, eaque pariatur dolorum eos temporibus quos.
          </p>
          <a href="#contact" class="button button--flex">
            Contact Me <i class="uil uil-message button__icon"></i>
          </a>
        </div>
      </div>

      <div class="home__scroll">
        <a href="#about" class="home__scroll-button button--flex">
          <i class="uil uil-mouse-alt home__scroll-mouse"></i>
          <span class="home__scroll-name">Scroll down</span>
          <i class="uil uil-arrow-down home__scroll-arrow"></i>
        </a>
      </div>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style>
.home__container {
  gap: 1rem;
}

.home__content {
  grid-template-columns: 0.5fr 3fr;
  padding-top: 3.5rem;
  align-items: center;
}

.home__social {
  display: grid;
  grid-template-columns: max-content;
  row-gap: 1rem;
}

.home__social-icon {
  font-size: 1.25rem;
  color: var(--first-color);
}

.home__social-icon:hover {
  color: var(--first-color-alt);
}

.home__blog {
  width: 200px;
  fill: var(--first-color);
}

.home__blob-img {
  width: 170px;
}

.home__data {
  grid-column: 1/3;
}

.home__title {
  font-size: var(--big-font-size);
}

.home__subtitle {
  font-size: var(--h3-font-size);
  color: var(--text-color);
  font-weight: var(--font-medium);
  margin-bottom: var(--mb-0-75);
}

.home__description {
  margin-bottom: var(--mb-2);
}

.home__scroll {
  display: none;
}

.home__scroll-button {
  color: var(--first-color);
  transform: 0.3s;
  -webkit-transform: 0.3s;
  -moz-transform: 0.3s;
  -ms-transform: 0.3s;
  -o-transform: 0.3s;
}

.home__scroll-button:hover {
  transform: translateY(0.25rem);
  -webkit-transform: translateY(0.25rem);
  -moz-transform: translateY(0.25rem);
  -ms-transform: translateY(0.25rem);
  -o-transform: translateY(0.25rem);
}

.home__scroll-mouse {
  font-size: 2rem;
}

.home__scroll-name {
  font-size: var(--small-font-size);
  color: var(--title-color);
  font-weight: var(--font-medium);
  margin-right: var(--mb-0-25);
}

.home__scroll-arrow {
  font-size: 1.25rem;
}
</style>
