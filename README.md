# product_landing_page



* {margin: 0; padding: 0; border: 0; outline: none;}
html, body {
	background-color: #efefef;
	color: #555555;
	font-size: 10px;
	font-family: "Times New Roman";
}
#header {
	padding-top: 2em;
@@ -15,16 +17,166 @@ html, body {
	#header-img {
		padding-top: 0.5em;
		padding-left: 2.50em;
		width: 35em;
		width: 30em;
	}
	#nav-bar {
		padding-right: 7em;
		display: inline-block;
		float: right;
	}
		#nav-bar div {
			padding: 0.5em 0.7em;
			font-size: 1.95em;
			display: inline-block;
		}
		.nav-link {
			color: #899889;
			text-decoration: none;
		}
			.nav-link:hover {
				color: #555555;
			}
.tag-line {
	margin-top: 4em;
	font-size: 5em;
	text-align: center;
	font-weight: 100;
}
#form {
	margin-top: 27em;
	margin: auto;
	margin-top: 10em;
	margin-bottom: 20em;
	width: 30em;
}
	#email {
		margin: auto;
		width: 100%;
		height: 3em;
		text-align: center;
		background-color: #eaeaea;
		color: #555555;
		border-radius: 0.7em;
		font-size: 2em;
		display: block;
	}
	#submit {
		margin: auto;
		margin-top: 1em;
		width: 10em;
		height: 2.1em;
		font-size: 2em;
		color: #cdcdcd;
		border-radius: 0.7em;
		display: block;
	}
#features {
	margin: auto;
	margin-bottom: 9em;
	display: flex;
	flex-direction: row;
}
	#features div {
		margin: 0.7em;
		flex: 1;
		text-align: center;
	}
		.icon {
			padding-bottom: 1em;
			font-size: 2.5em;
		}
		.icon-title {
			padding-bottom: 1em;
			font-size: 2.5em;
		}
		.icon-feature {
			font-size: 1.95em;
			line-height: 1.5;
		}
#works {
	margin: auto;
	width: 60vw;
	height: 34vw;
	margin-top: 10em;
}
	#video {
		margin: auto;
		width: 100%;
		height: 100%;
		display: block;
	}
#pricing {
	margin: auto;
	margin-top: 9em;
	margin-bottom: 5em;
	display: flex;
	flex-direction: row;
}
	#pricing div {
		margin: 0.7em;
		flex: 1;
		text-align: center;
	}
		#pricing div h1 {
			margin-top: 4.5em;
			font-size: 3em;
		}
		#pricing div h2 {
			margin-top: 1.5em;
			font-size: 2em;
		}
		#pricing div button {
			margin-top: 1.5em;
			width: 50%;
			height: 2em;
			font-size: 2em;
			background-color: #555555;
			color: #efefef;
			border-radius: 2em;
			cursor: pointer;
		}
.footer {
	margin-top: 10em;
	padding-top: 1em;
	background-color: #eaeaea;
}
@media only screen and (max-width: 600px) {
	.footer div {
		padding: 1em;
		font-size: 1.45em;
		text-align: right;
	}
		.footer div span {
			margin-right: 2.1em;
		}
@media only screen and (max-width: 860px) {
	html, body {
		background-color: #cdcdcd;
	}
	#header-img {
		padding-left: 0;
		margin: auto;
		display: block;
	}
	#nav-bar {
		margin-top: 3.5em;
		padding: 0;
		display: block;
		float: none;
	}
		#nav-bar div {
			display: block;
			text-align: center;
		}
	.tag-line {
		margin-top: 6em;
	}
	#features {
		flex-direction: column;
	}
	#works {
		width: 90vw;
		height: 51vw;
	}
	#pricing {
		flex-direction: column;
	}
} 


<div><a href="#pricing" class="nav-link">Pricing</a></div>
		</nav>
	</header>
	<div>
		<h1 class="tag-line">Handcrafted, Home-made Masterpieces</h1>
	</div>
	<form action="https://www.freecodecamp.com/email-submit" id="form">
		<input type="email" name="email" id="email" placeholder="your email id" required>
		<input type="submit" name="send" id="submit">
		<input type="submit" value="Send" id="submit">
	</form>
	<main id="features">
		<div>
			<div><i class="fa fa-3x fa-fire" aria-hidden="true"></i></div>
			<h1>Premium Materials</h1>
			<div>Our trombones use the shiniest brass which is sourced locally. This will increase the longevity of your purchase.</div>
			<div class="icon"><i class="fa fa-3x fa-fire" aria-hidden="true"></i></div>
			<h1 class="icon-title">Premium Materials</h1>
			<div class="icon-feature">Our trombones use the shiniest brass which is sourced locally. This will increase the longevity of your purchase.</div>
		</div>
		<div>
			<div><i class="fa fa-3x fa-truck" aria-hidden="true"></i></div>
			<h1>Fast Shipping</h1>
			<div>We make sure you recieve your trombone as soon as we have finished making it. We also provide free returns if you are not satisfied.</div>
			<div class="icon"><i class="fa fa-3x fa-truck" aria-hidden="true"></i></div>
			<h1 class="icon-title">Fast Shipping</h1>
			<div class="icon-feature">We make sure you recieve your trombone as soon as we have finished making it. We also provide free returns if you are not satisfied.</div>
		</div>
		<div>
			<div><i class="fa fa-3x fa-battery-full" aria-hidden="true"></i></div>
			<h1>Quality Assurance</h1>
			<div>For every purchase you make, we will ensure there are no damages or faults and we will check and test the pitch of your instrument.</div>
			<div class="icon"><i class="fa fa-3x fa-battery-full" aria-hidden="true"></i></div>
			<h1 class="icon-title">Quality Assurance</h1>
			<div class="icon-feature">For every purchase you make, we will ensure there are no damages or faults and we will check and test the pitch of your instrument.</div>
		</div>
	</main>
	<section id="works">
		<iframe id="video" src="https://www.youtube-nocookie.com/embed/y8Yv4pnO7qc?rel=0&amp;controls=0&amp;showinfo=0" frameborder="0" allowfullscreen></iframe>
	</section>
	<section id="pricing"></section>
	<section id="pricing">
		<div>
			<h1>TENOR TROMBONE</h1>
			<h2>$600</h2>
			<button>Select</button>
		</div>
		<div>
			<h1>BASS TROMBONE</h1>
			<h2>$600</h2>
			<button>Select</button>
		</div>
		<div>
			<h1>VALVE TROMBONE</h1>
			<h2>$600</h2>
			<button>Select</button>
		</div>
	</section>
	<footer class="footer">
		<div>
			<span>Privacy</span><span>Terms</span><span>Contact</span>
		</div>
		<div>Copyright 2018, Original Trombones</div>
	</footer>
	<script type="text/javascript" src="https://cdn.freecodecamp.org/testable-projects-fcc/v1/bundle.js"></script>
</body>
</html>
