<script>
	import MoonCalendar from './sections/MoonCalendar.svelte';
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
		min-height: 100vh;
		padding: 2em;
		position: relative;
	}
	.head {
		background:  linear-gradient(0deg, #dfffdb, #ffffff);
	}
	.feature_notifications {
		background:  linear-gradient(0deg, #8eff80, #b9ffb0);
	}
	.feature_planning {
		background:  linear-gradient(0deg, #72ff61, #8eff80);
	}
	.feature_acoustic_growth {
		background:  linear-gradient(0deg, #54ff40, #72ff61);
	}
	.feature_multicavo {
		background:  linear-gradient(0deg, #36ff1f, #54ff40);
	}
</style>

<section class="head">
	<h2>avoca.to - do all the avocado things!</h2>
</section>
<MoonCalendar />
<section class="feature_notifications">
	<h2>avoca.to reminds you to be there for your plants.</h2>
	<p>receive push notifications reminding you to take care of your avocado growing operation. Enable and disable different reminders, like watering, to fit your life.</p>
</section>
<section class="feature_planning">
	<h2>long term planning</h2>
	<p>Track the time and care you invest into your avocado and receive useful tips. </p>
</section>
<section class="feature_acoustic_growth">
	<h2>Acoustic Growth Stimulation</h2>
	<p>connect your avocados to other avoca.to users around the world and let them talk to each other. Stream your fav piece by Mozart straight to them green goodies.</p>
</section>
<section class="feature_multicavo">
<h2>
	Multicavo.
</h2>
<p>Effortlessly manage large-scale (like 5 plant) operations even if they were planted at different times.</p>
</section>

