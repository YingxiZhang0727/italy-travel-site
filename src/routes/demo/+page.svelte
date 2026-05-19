<script lang="ts">
	import { resolve } from '$app/paths';
</script>

<a href={resolve('/demo/playwright')}>playwright</a>
<h1>Italy Travel Guide</h1>

<p>Discover Milano, Roma and Perugia.</p>

<nav>
  <a href="/">Home</a>
</nav>

<style>
  h1 {
    font-size: 48px;
    color: darkred;
  }

  p {
    font-size: 24px;
  }

  nav {
    margin-top: 20px;
  }

  a {
    font-size: 20px;
    color: black;
  }
</style>