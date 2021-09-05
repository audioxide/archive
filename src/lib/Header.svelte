<script>
</script>

<header class="navbar">
	<a href="/" class="audioxide-archive-logo hide-on-mobile"
		><span class="logo">Audioxide</span> Archive</a
	>
	<a href="https://audioxide.eo.page/newsletter"
		><span class="subscription-prompt"
			>Subscribe <span class="hide-on-mobile">for monthly roundups</span
			></span
		> →</a
	>
	<nav class="dropdown">
		<button class="dropbtn"
			>Browse editions
			<i class="fa fa-caret-down" />
		</button>
		<div class="dropdown-content">
			<a href="/2021-08">August 02021</a>
			<a href="/2021-07">July 02021</a>
			<a href="/2021-06">June 02021</a>
			<a href="/2021-05">May 02021</a>
			<!--            <a href="/2021-04">April 02021</a>-->
			<!--            <a href="/2021-03">March 02021</a>-->
			<!--            <a href="/2021-02">February 02021</a>-->
			<!--            <a href="/2021-01">January 02021</a>-->
			<!--            <a href="/2020-12">December 02021</a>-->
			<!--            <a href="/2020-11">November 02021</a>-->
		</div>
	</nav>
</header>

<style>
	.audioxide-archive-logo {
		border-right: 2px solid #f5f5f5;
		font-weight: 700;
	}

	.navbar {
		background-color: #222;
		font-family: "Source Sans Pro", sans-serif;
		box-shadow: 0 3px 6px 0 rgba(0, 0, 0, 0.3);
		position: fixed;
  top: 0;
  width: 100%;
		z-index: 1;
	}

	.navbar a {
		float: left;
		font-size: 20px;
		color: white;
		text-align: center;
		padding: 14px 16px;
		text-decoration: none;
	}

	.dropdown {
		float: right;
		overflow: hidden;
	}

	.dropdown .dropbtn {
		font-size: 20px;
		border: none;
		outline: none;
		color: white;
		padding: 14px 16px;
		background-color: inherit;
		font-family: inherit;
		margin: 0;
	}

	.navbar a:hover,
	.dropdown:hover .dropbtn {
		background-color: #f5f5f5;
		color: #282828;
	}

	.dropdown-content {
		display: none;
		position: absolute;
		background-color: #f9f9f9;
		width: 165px;
		box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
		z-index: 1;
	}

	.dropdown-content a {
		font-size: 16px;
		float: none;
		color: black;
		padding: 12px 16px;
		text-decoration: none;
		display: block;
		text-align: left;
	}

	.dropdown-content a:hover {
		background-color: #ddd;
	}

	.dropdown:hover .dropdown-content {
		display: block;
	}

	.subscription-prompt {
		text-decoration: underline;
	}

	@media screen and (max-width: 600px) {
		.hide-on-mobile {
			visibility: hidden;
			display: none;
		}
	}
</style>
