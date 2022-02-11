
<main>
	<div class="contents">
		<img class="portrait" src="assets/images/Portrait.png" alt="Portrait"/>
		<div class="title">
			<h1>Acerola</h1>
			<p>Technical Artist :: Graphics Programmer :: Game Developer</p>
			<div class="social-media">
				<a href="https://www.youtube.com/c/acerola_t" target="_blank">
					<img class="social-icon" src="assets/images/youtube-icon.png" alt="Youtube"/>
				</a>
				<a href="https://www.twitter.com/acerola_t" target="_blank">
					<img class="social-icon" src="assets/images/twitter-icon.png" alt="Twitter"/>
				</a>
				<a href="https://www.twitch.com/acerola_t" target="_blank">
					<img class="social-icon" src="assets/images/twitch-icon.png" alt="Twitch"/>
				</a>
				<a href="https://github.com/GarrettGunnell" target="_blank">
					<img class="social-icon" src="assets/images/github-icon.png" alt="Github"/>
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
		height: 50%;
		left: 52%;
		display: inline-block;
		text-align: center;
	}

	p {
		font-size: 2.05vh;
		font-family: "Noto Serif JP";
		color: #752b36;
		margin-bottom: 2%;
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
		height: 25%;
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
		filter: invert(89%) sepia(100%) saturate(0%) hue-rotate(21deg) brightness(108%) contrast(103%);
	}

	.social-icon:hover {
		height: 4.5vh;
		width: auto;
		margin-top: 1vh;
		margin-left: 0.75vw;
		margin-right: 0.75vw;
		filter: invert(29%) sepia(38%) saturate(887%) hue-rotate(302deg) brightness(101%) contrast(83%);
		cursor: pointer;
	}

</style>