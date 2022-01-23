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
				<img class="social-icon" src={youtubeIconSource} alt="Youtube" on:mouseover={youtubeHoverIn} on:mouseout={youtubeHoverOut}/>
				<img class="social-icon" src={twitterIconSource} alt="Twitter" on:mouseover={twitterHoverIn} on:mouseout={twitterHoverOut}/>
				<img class="social-icon" src={twitchIconSource} alt="Twitch" on:mouseover={twitchHoverIn} on:mouseout={twitchHoverOut}/>
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
		font-size: 2vh;
		font-family: 'Kozuka Mincho Pro';
		src: url('/assets/fonts/KozMinPro.otf') format('otf');
		font-weight: 300;
		color: #74303a;
		margin-top: 1%;
	}

	h1 {
		font-size: 10vh;
		font-family: 'Kozuka Mincho Pro';
		src: url('/assets/fonts/KozMinPro.otf') format('otf');
		font-weight: 600;
		color: #FFFFFF;
		-webkit-text-stroke: 0.2vh #a4958e;
		text-shadow: 0.5vh 0.35vh #984652;
		margin-bottom: -10%;
	}

	.portrait {
		height: 90%;
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
		cursor: pointer;
	}
</style>