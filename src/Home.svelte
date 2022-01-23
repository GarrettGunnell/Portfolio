<main>
	<div class="contents">
		<img class="portrait" src="assets/images/Portrait.png" alt="Portrait"/>
		<div class="title">
			<h1>Acerola</h1>
			<p>Technical Artist | Graphics Programmer | Game Developer</p>
			<div class="social-media">
				<img class="social-icon" src="assets/images/youtube-icon.png" alt="Youtube"/>
				<img class="social-icon" src="assets/images/twitter-icon.png" alt="Twitter"/>
				<img class="social-icon" src="assets/images/twitch-icon.png" alt="Twitch"/>
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
		height: 4vh;
		width: auto;
		margin-top: 1vh;
		margin-left: 0.75vw;
		margin-right: 0.75vw;
	}
</style>