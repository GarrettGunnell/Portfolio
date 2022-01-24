<script>
	let youtubeIconSource = "assets/images/youtube-icon.png";
	let twitterIconSource = "assets/images/twitter-icon.png";
	let twitchIconSource = "assets/images/twitch-icon.png";

	function youtubeHoverIn(e) {
		youtubeIconSource = "assets/images/youtube-icon-stroke.png";
	}
	
	function youtubeHoverOut(e) {
		youtubeIconSource = "assets/images/youtube-icon.png";
	}

	function twitterHoverIn(e) {
		twitterIconSource = "assets/images/twitter-icon-stroke.png";
	}
	
	function twitterHoverOut(e) {
		twitterIconSource = "assets/images/twitter-icon.png";
	}

	function twitchHoverIn(e) {
		twitchIconSource = "assets/images/twitch-icon-stroke.png";
	}
	
	function twitchHoverOut(e) {
		twitchIconSource = "assets/images/twitch-icon.png";
	}
</script>


<main>
	<div class="contents">
		<img class="portrait" src="assets/images/Portrait.png" alt="Portrait"/>
		<div class="title">
			<h1>Acerola</h1>
			<p>Technical Artist | Graphics Programmer | Game Developer</p>
			<div class="social-media">
				<a href="https://www.youtube.com/c/acerola_t" target="_blank" on:mouseover={youtubeHoverIn} on:mouseout={youtubeHoverOut}>
					<img class="social-icon" src={youtubeIconSource} alt="Youtube"/>
				</a>
				<a href="https://www.twitter.com/acerola_t" target="_blank" on:mouseover={twitterHoverIn} on:mouseout={twitterHoverOut}>
					<img class="social-icon" src={twitterIconSource} alt="Twitter"/>
				</a>
				<a href="https://www.twitch.com/acerola_t" target="_blank" on:mouseover={twitchHoverIn} on:mouseout={twitchHoverOut}>
					<img class="social-icon" src={twitchIconSource} alt="Twitch"/>
				</a>
			</div>
		</div>
	</div>
</main>

<style>
	main {
		height: 100%;
		width: 100%;
		background-color: #a4958e;
	}

	.contents {
		height: 100%;
		display: flex;
		align-items: center;
		justify-content: center;
	}

	.title {
		position: absolute;
		top: 25%;
		height: 20%;
		left: 52%;
		display: inline-block;
		text-align: center;
	}

	p {
		font-size: 2.05vh;
		font-family: "Noto Serif";
		color: #74303a;
		margin-top: 1%;
		margin-bottom: 1%;
	}

	h1 {
		font-size: 11vh;
		font-family: 'Libre Baskerville', serif;
		transform: scaleX(0.9);
		letter-spacing: 0.1vh;
		font-weight: 400;
		color: #FFFFFF;
		-webkit-text-stroke: 0.2vh #a4958e;
		text-shadow: 0.5vh 0.35vh #984652;
		height: 60%;
	}

	.portrait {
		height: 90vh;
		padding-right: 6.5%;
	}

	.social-media {
		display: flex;
		align-items: center;
		justify-content: center;
	}

	.social-icon {
		height: 4.5vh;
		width: auto;
		margin-top: 1vh;
		margin-left: 0.75vw;
		margin-right: 0.75vw;
	}

	a {
		cursor: pointer;
	}
</style>