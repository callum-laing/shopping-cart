<header>
    <div>
        <h1>Shopping Cart</h1>
    </div>

<div>
    <nav>
        <a href="/">Home</a>
        <a href="/">Products</a>
        <a href="/cart">About Us</a>
    </nav>
</div>
<button class="shoppingCart">
    <span>
        <img class="cartImage" src="../src/images/shopping-cart.png" alt="">
    </span>
</button>
</header>


<style>
    header {
    display: flex;
    align-items: center;
    justify-content: space-around;
    padding: 1rem;
}

h1 {
    color: white;
}

nav {
	display: flex;
	justify-content: center;
	align-content: center;
	gap: 50px;
	padding: 20px;
}

a {
	text-decoration: none;
	color: rgba(200, 200, 250);
	font-family: 'Fjalla One', sans-serif;
	letter-spacing: 4px;
}

a:hover {
	color: #ccd0e8;
}

.shoppingCart {
    background-color: transparent;
    border: none;
}

.shoppingCart:hover {
    cursor: pointer;
}

.cartImage {
        filter: invert(100%);
    }


</style>