# Hackathon-Project-1

"C:\Users\caiphus Laka\New folder\week3.html\w3.html\project.html\project.html"

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <lik rel="stylesheet" href="style/style.css">
        <title>YAPPIZ STORE</title>
    </head>
    <style>
        body {
            background-color: antiquewhite;
        }
        div {
            border: 3px solid black;
            padding: 30;
        }
        img {
            margin: 10px;
        }
    </style>
    <body>
        <header>
            <div  class="logo"></div>
            <img src="C:\Users\caiphus Laka\New folder\pexels-artempodrez-6787035.jpg" width="400" height="300">
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#menu">Menu</a></li>
                    <li><a href="#cart">Cart</a></li>
                    <li><a href="#contact">contact</a></li>
                    <li><a href="#log in">Log in / sign up</a></li>
                </ul>
            </nav>
        </header>
        <div class="search for">
            <input type="text" placeholder="search products">
            <button>Search</button>
        </div>
    </body>
    <h1 style="color: orangered; font-weight: 500">The Home of fashion</h1>
    <p>Born from a passion for design and innovation, YAPPIZ STORE offers the latest in fashion trends, providing you with clothing and accessorie that excude elegance and confidence</p>
    <div>
        <img src="C:\Users\caiphus Laka\New folder\pexels-bohlemedia-1884579.jpg" width="400" height="300">
        <div class="product">
                <h3>Filter by Cateegory</h3>
            <img src="C:\Users\caiphus Laka\New folder\week3.html\w3.html\project.html\pexels-romanp-16170.jpg" width="300" height="200">
            <span class="price">R599</span>
            <button class="buy-now">Buy Now</button>
            <select id="size">
                <option value="S">S</option>
                <option value="M">M</option>
                <option value="L">L</option>
                <option value="XL">XL</option>
            </select>
            <img src="C:\Users\caiphus Laka\New folder\week3.html\w3.html\project.html\pexels-pixabay-52518.jpg" width="300" height="200">
            <span class="price">R450</span>
            <button class="buy-now">Buy Now</button>
            <select id="size">
                <option value="UK">28</option>
                <option value="UK">30</option>
                <option value="UK">32</option>
                <option value="UK">38</option>
                </select>
            <img src="C:\Users\caiphus Laka\New folder\week3.html\w3.html\project.html\pexels-fatihkaya-13640239.jpg" width="300" height="200">
            <span class="price">R350</span>
            <button class="buy-now">Buy Now</button>
            <select id="size">
                <option value="S">S</option>
                <option value="M">M</option>
                <option value="L">L</option>
                <option value="XL">XL</option>
                </select>
            <img src="C:\Users\caiphus Laka\New folder\week3.html\w3.html\project.html\pexels-1242304473-30156646.jpg" width="300" height="200">
            <span class="price">R900</span>
            <button class="buy-now">Buy Now</button>
            <select id="size">
                <option value="UK">34</option>
                <option value="UK">36</option>
                <option value="UK">38</option>
                <option value="UK">40</option>
                </select>
            <img src="C:\Users\caiphus Laka\New folder\week3.html\w3.html\project.html\pexels-lum3n-44775-251454.jpg" width="300" height="200">
            <span class="price">R90</span>
            <button class="buy-now">Buy Now</button>
            <select id="size">
                <option value="S">S</option>
                <option value="M">M</option>
                </select>
            <img src="C:\Users\caiphus Laka\New folder\pexels-dom-j-7304-45982.jpg" width="300" height="200">
            <span class>R250</span>
            <button class="buy-now">Buy Now</button>
            <select id="size">
                <option value="S">S</option>
                <option value="M">M</option>
                <option value="L">L</option>
                <option value="XL">XL</option>
            </select>
            <div>
                <button class="add-to-cart">Add to cart</button>
            </div>
    </div>
    <footer>
        <section class="checkout">
            <h2>Checkout</h2>
            <!-- Order Summary -->
             <div class="order-summary">
                <h3>Your Order</h3>
                <table border="1">
                    <tr>
                        <th>Item</th>
                        <th>Price</th>
                        <th>Quality</th>
                        <th>Total</th>
                    </tr>
                    <tr>
                        <td>Baige Jacket</td>
                        <td>R90</td>
                        <td>1</td>
                        <td>R90</td>
                    </tr>
                </table>
                <p><strong>Total:</strong></p>
             </div>
            <form action=" /submit-order"method="post">
                <!-- Customer information -->
                 <h2>Billing Information</h2>
                 <label for="name">Full Name</label>
                 <input type="text" id="name" name="name" required>
                 
                 <label for="email"> Email Address</label>
                 <input type="email" id="email" name="email" required>

                  <!-- Shipping Address -->
                  <label for="address">Shipping Address</label>
                  <textarea id="address" name="address" required></textarea>
                 <label for="phone">Phone Number.</label>

                 <!-- Shipping State -->
                  <label for=="State">State:</label>
                  <input type="text" id="state" name="state" required>

                  <!-- Shipping Zip Code -->
                   <label for="zip">Zip Code</label>
                   <input type="text" id="zip" name="zip" required>

                   <!--Shipping Country-->
                   <label for="country">Country</label>
                   <input type="type" id="country" name="country" required>

                 <h3>Payment Information</h3>

                  <!-- Credit Card Information -->
                   <labe for="card number">Card Number</label>
                    <input type="text" id="card number" name="card number" required>
                    
                    <!-- Expiration Date -->
                     <label for="exp-date"> Expiration Date</label>
                     <input type="month" id="exp-date" name="exp-date" required>

                     <!-- CW -->
                      <label for="cvv">CVV</label>
                      <input type="text" id="cvv" name="cvv" required>

                  <div class="payment-logos">
                    <img src="C:\Users\caiphus Laka\New folder\week3.html\w3.html\project.html\pexels-theshuttervision-8811453.jpg" width=300 height="200">
                    <img src="C:\Users\caiphus Laka\New folder\week3.html\w3.html\project.html\pexels-introspectivedsgn-8363135.jpg" width="300" height="200">
                    <button type="submit"> Complete Purchase</button>
                  </div>
            </form>
        </section>
        <section>
            <h2>About Us</h2>
            <p>At YAPPIZ STORE, we believe that style should empower you, make you feel confident, and
                be as unique as you are. we are a fashion brand from a passion for quality clothing that
                quality cloting that blends timeless design with trends.</p>
        </section>
        <div>
            <p>& copy; 2025 Yappiz Store. All Rights Reserved.</p>
        </div>
    </div>
        <h3>Contact Us</h3>
        <ul>
            <li>Email: ciphuslaka98@gmail.com</li>
            <li>Phone: +27 782 433 103</li>
            <li>Adress: South Africa, Limpopo, Thabazimbi</li>
        </ul>
        <h3>Quick Links</h3>
        <ul>
            <li><a href="#terms">Terms of service</a></li>
            <li><a href="#policy"></a>Policy</li>
            <li><a href="#Shipping">Shipping & Returns</a></li>
        </ul>
        <div>
            <h3>Follow us</h3>
            <div class="social-media">
                <a href="#">Facebook</a>
                <a href="#"> Instagram</a>
            </div>
            <form class="newsletter">
                <label for="emai">Subscribe to our newsletter:</label>
                <input type="email" id="email" placeholder="Enter your email">
                <button type="submit"> Subscribe</button>
    </footer>
</html>
