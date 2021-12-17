<script>
	import Nav from './Nav.svelte'
	import Footer from './Footer.svelte'
</script>

<div>
	<Nav />
	<h1>About the Initiative.</h1>
	<p>
		Started in 2011, Cup of Uji fights hunger among less privileged primary school children in Kenya by providing one cup of uji (porridge), in school each day. Cup of Uji seeks to drive their education, and, in the long term, alleviate poverty.
	</p>
	<form action="https://secure.changa.co.ke/myweb/share/32709" method="post">
		<button type="submit">Contribute &#8594;</button>
	</form>
	<Footer />
</div>

<style>
	div {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		position: absolute;
		top: 0;
		margin: 1.5em;
	}
	button {
		font-weight: 400;
		font-size: 1.45em;
		background: transparent;
		border: 3px solid #bc4749;
		border-radius: 8px;
		box-shadow: .15em .15em .15em #a7c957;
		color: #f2e8cf;
		margin-top: .5em;
		padding: .2em;
		outline:  none;
	}
	button:hover {
		cursor: pointer;
		background-color: #fff;
		color: green;
	}
	p {
		text-align: center;
		color: #f2e8cf;
		font-weight: 300;
		font-size: 1.2em;
		margin-bottom:  .8em;
	}
	h1 {
		font-size: 1.8em;
		font-weight: 500;
		color: #a7c957;
		margin: .8em;
		text-align: left;
	}
	@media (min-width: 640px) {
		div {
			margin: 1em;
		}
		p {
			width: 60%;
			font-size: 1em;
			margin: 0;
		}
		h1 {
			margin: 0 0 .3em 0;
		}
	}
</style>