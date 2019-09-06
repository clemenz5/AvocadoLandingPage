<script>
	import MoonCalendar from './sections/MoonCalendar.svelte';
	import Notifications from './sections/Notifications.svelte';
	import Multicado from "./sections/Multicado.svelte";
</script>

<style>
	:global(html, body) {
		margin: 0;
		padding: 0;
		font-size: 18px;
		overflow-x: hidden;
	}
	:global(h1, h2) {
		font-size: 2em;
		margin: 0 0 1.5em 0;
		text-align: center;
	}
	:global(section) {
		height: 100vh;
		padding: 2em;
		padding-top: 350px;
		position: relative;
		box-sizing: border-box;
	}
	:global(p) {
    	max-width: 80%;
    	margin: auto;
  	}
	.head {
		background:  linear-gradient(0deg, #dfffdb, #ffffff);
	}
	.feature_planning {
		background:  linear-gradient(0deg, #72ff61, #8eff80);
	}
	.feature_acoustic_growth {
		background:  linear-gradient(0deg, #54ff40, #72ff61);
	}
</style>

<section class="head">
	<h2>avoca.to - do all the avocado things!</h2>
</section>
<MoonCalendar />
<Notifications />
<section class="feature_planning">
	<h2>long term planning</h2>
	<p>Track the time and care you invest into your avocado and receive useful tips. </p>
</section>
<section class="feature_acoustic_growth">
	<h2>Acoustic Growth Stimulation</h2>
	<p>connect your avocados to other avoca.to users around the world and let them talk to each other. Stream your fav piece by Mozart straight to them green goodies.</p>
</section>
<Multicado></Multicado>

