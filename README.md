
<!DOCTYPE html>

<html>

<head>

	<title>OurWebsite</title>

	<link rel="stylesheet" type="text/css" href="style.css">

</head>

<body>

	<header>

		<h1>OurWebsite</h1>

		<nav>

			<ul>

				<li><a href="#">Home</a></li>

				<li><a href="#">Shop</a></li>

				<li><a href="#">Cart</a></li>

				<li><a href="#">Contact</a></li>

			</ul>

		</nav>

	</header>

		<main>

		<section class="product">

			<h2>Product Name</h2>

			<img src="product-image.jpg">

			<p>Product Description</p>

			<button>Add to Cart</button>

		</section>

		

		<section class="product">

			<h2>Product Name</h2>

			<img src="product-image.jpg">

			<p>Product Description</p>

			<button>Add to Cart</button>

		</section>

		

		<section class="product">

			<h2>Product Name</h2>

			<img src="product-image.jpg">

			<p>Product Description</p>

			<button>Add to Cart</button>

		</section>

	</main>

	

	<footer>

		<p>&copy; OurWebsite</p>

	</footer>

	

	<script src="script.js"></script>

</body>

</html>

body {

	font-family: Arial, sans-serif;

	margin: 0;

	padding: 0;

}

header {

	background-color: #333;

	color: #fff;

	display: flex;

	justify-content: space-between;

	align-items: center;

	padding: 1rem;

}

nav ul {

	list-style: none;

	margin: 0;

	padding: 0;

	display: flex;

}

nav ul li {

	margin-right: 1rem;

}

nav ul li a {

	color: #fff;

	text-decoration: none;

}

main {

	display: flex;

	flex-wrap: wrap;

	justify-content: space-around;

	padding: 2rem;

}

.product {

	background-color: #f7f7f7;

	border-radius: 5px;

	box-shadow: 0px 3px 5px rgba(0, 0, 0, 0.1);

	margin-bottom: 2rem;

	padding: 1rem;

	text-align: center;

	max-width: 300px;

}

.product img {

	max-width: 100%;

}

.product h2 {

	font-size: 1.5rem;

	margin-top: 0;

}

.product button {

	background-color: #333;

	border: none;

	border-radius: 5px;

	color: #fff;

	cursor: pointer;

	font-size: 1rem;

	margin-top: 1rem;

	padding: 0.5rem 1rem;

}

.product button:hover {

	background-color: #555;

}

footer {

	background-color: #333;

	color: #fff;

	padding: 1rem;

	text-align: center;

}

@media (max-width: 768px) {

	main {

		flex-direction: column;

		align-items: center;

	}

	

	.product {

		max-width: 100%;

	}

}
