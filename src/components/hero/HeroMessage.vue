<template>
  <div>
    <h1>Jessé Sousa</h1>
    <p class="job-title">Front-End Developer</p>
    <p class="email">jesse@jessesousa.com</p>
    <div class="icons">
      <a href="https://github.com/JesseSousa" target="_blank">
        <i class="fa-brands fa-github"></i>
      </a>
      <a
        href="https://www.linkedin.com/in/jess%C3%A9-sousa-desenvolvendor/"
        target="_blank"
      >
        <i class="fa-brands fa-linkedin"></i>
      </a>
      <a href="https://dev.to/jessesousa" target="_blank">
        <i class="fa-brands fa-dev"></i>
      </a>
    </div>
  </div>
</template>

<style scoped>
div {
  color: #fff;
  text-align: center;
}

h1 {
  font-size: 4rem;
  font-weight: 400;
  color: #ffd60a;
  text-shadow: 6px 6px 8px #222;
}

p.job-title {
  font-size: 1.5rem;
}

p.email {
  font-size: 1.15rem;
  color: #ccc;
}

.icons {
  margin-top: 1rem;
}

.icons a {
  text-decoration: none;
  transition: opacity 0.25s;
  opacity: 0.75;
}

.icons a:hover {
  opacity: 1;
}
.icons i {
  color: #fff;
  font-style: normal;
  font-size: 2.5rem;
  padding: 0 0.5rem;
}
</style>
