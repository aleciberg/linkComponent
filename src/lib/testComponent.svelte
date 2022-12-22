<script></script>

<div class="large-container">
	<div class="small-container">
		<a href="https://linkedin.com/in/aleciberg" class="link"><span>LinkedIn</span></a>
		<a class="link" href="https://github.com/aleciberg"><span>GitHub</span></a>
		<a class="link"><span>Email</span></a>
		<a class="link"><span>Another Email</span></a>
		<a class="link"><span>Random Links</span></a>
	</div>
</div>

<!-- build reusable component- link page for devs
eventually store values in file they edit and then can use
bundle icons they can choose from: ie github or linkedin or whatever -->
<style>
	.large-container {
		background-color: white;
		width: 30vw;
		height: 60vh;
		border-radius: 50px 50px 0 0;
	}

	.small-container {
		display: flex;
		flex-direction: column;
		border: 2px said blue;
		margin-top: 15px;
		padding-top: 20px;
	}

	.link {
		border: 1px #bcbcbc;
		color: rgb(55, 62, 97);
		box-shadow: 4px 4px 18px -5px rgba(100, 100, 200, 0.68);
		border-radius: 16px;
		height: 50px;
		width: 80%;
		padding-top: 0 20px;
		margin: 15px auto;
		align-items: center;
		display: flex;
	}

	span {
		padding: 0 20px;
	}
</style>
