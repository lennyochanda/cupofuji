<nav>
	<img src="/images/logo.png" alt="logo">
	<ul>
		<li><a href="/">home</a></li>
		<li><a href="/gallery">gallery</a></li>
		<li><a href="/about">about</a></li>
		<li><a href="/contact">contact</a></li>
	</ul>
</nav>

<style>
	nav {
		width: 100%;
		height: 3em;
		background: transparent;
		display: flex;
		justify-content: space-between;
		align-items: center;
		z-index: 10;
		flex-wrap: wrap;
		padding: .5em;
	}
	img {
		height: 40px;
		width: 40px;
		border-radius: 50%;
	}
	ul {
		list-style: none;
		display: flex;
		justify-content: space-around;
	}
	a {
		color: #eee;
		font-weight: 350;
		font-size: 1em;
	}
	a:hover {
		color: #bc4749;
	}
	@media (min-width: 640px) {
		ul {
			width: 50%;
		}
	}
</style>