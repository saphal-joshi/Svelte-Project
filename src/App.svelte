<script>
	import Card from './Card.svelte';
  </script>
  
  <main>
	<h1>NBA Finals 2023</h1>
	<p>Visit the <a href="https://www.espn.com/nba/">Saphal Joshi</a> ESPN website to learn more about the game.</p>
	<Card />
  </main>
  
  <style>
	main {
	  text-align: center;
	  padding: 1em;
	  max-width: 240px;
	  margin: 0 auto;
	}
  
	h1 {
	  color: #ff3e00;
	  text-transform: uppercase;
	  font-family: Georgia, 'Times New Roman', Times, serif;
	  font-size: 4em;
	  font-weight: 100;
	}
  
	@media (min-width: 640px) {
	  main {
		max-width: none;
	  }
	}
  </style>
  