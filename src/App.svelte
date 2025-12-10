<script>
  import githubLogo from "./assets/github.svg";
  import linkedinLogo from "./assets/linkedin.png";
</script>

<h1>Luca Hartweger</h1>

<div class="">
  <a href="https://github.com/sunti27">
    <img src={githubLogo} alt="GitHub" class="logo github-logo" />
  </a>
  <a href="https://linkedin.com/in/luca-hartweger">
    <img src={linkedinLogo} alt="LinkedIn" class="logo" />
  </a>
</div>

<style>
  img.logo {
    width: 2rem;
  }

  img.github-logo {
    border-radius: 100%;
    border: 1px solid white;
    background-color: white;
    width: calc(2rem - 2px);
  }
</style>
