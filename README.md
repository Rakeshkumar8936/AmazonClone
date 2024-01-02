# AmazonClone

This is a Clone website projet of Amazon.
Made with the help from Mentor.
# made using HTML AND CSS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Amazon</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css" integrity="sha512-iecdLmaskl7CVkqkXNQ/ZH/XLlvWZOJyj7Yy7tcenmpD1ypASozpmT/E0iPtmFIB46ZmdtAc9eNBvH0H/ZpiBw==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="style.css">
</head>
<body>
<header>    
    <div class="navbar">
        <div class="nav-logo border">
            <div class="logo"></div>
        </div>
        <div class="nav-address border">
            <p class="address-first">Deliver to</p>
            <div class="address-icon">
                <i class="fa-sharp fa-solid fa-location-dot"></i>
                <p class="address-second">India</p>
            </div>
        </div>
        <div class="nav-search">
            <select class="search-select">
                <option>All</option>
            </select>
            <input placeholder="Search Amazon" class="search-input">
            <div class="search-icon"><i class="fa-solid fa-magnifying-glass"></i></div>
        </div>
        <div class="nav-SignIn border">
            <p><span>Hello, Sign in</span></p>
            <p class="nav-second">Account & lists</p>
        </div>
        <div class="nav-returns border">
            <p><span>Returns</span></p>
            <p class="nav-second">&Orders</p>
        </div>
        <div class="nav-cart border">
            <i class="fa-solid fa-cart-shopping"></i>
            <p>cart</p>
        </div>
    </div>

    <div class="panel">
        <div class="panel-all">
            <i class="fa-solid fa-bars"></i>
            All
        </div>
        <div class="panel-options">
            <p>Today's Deals</p>
            <p>Customer Service</p>
            <p>Registry</p>
            <p>Gift Cards</p>
            <p>Sell</p>
            
        </div>
        <div class="panel-deals">
            Shop deals in Electronics
        </div>
    </div>

</header>

<div class="hero-section">
    <div class="hero-msg">You are on amazon.com. You can also shop on Amazon India for millions of products with fast local delivery. <a href="">Click here to go to amazon.in</a> </div>
</div>

    <div class="shop-section">
        <div class="box1 box">
            <div class="box-content">
                <h2>Clothes</h2>
            <div class="box-image" style="background-image: url('box1_image.jpg')"></div>
            <p>see more</p>
            </div>    
        </div>
        <div class="box2 box"><div class="box-content">
            <h2>Health & Personal Care</h2>
        <div class="box-image" style="background-image: url('box2_image.jpg')"></div>
        <p>see more</p>
        </div></div>
        <div class="box3 box"><div class="box-content">
            <h2>Furnitures</h2>
        <div class="box-image" style="background-image: url('box3_image.jpg')"></div>
        <p>see more</p>
        </div></div>
        <div class="box4 box"><div class="box-content">
            <h2>Gadgets</h2>
        <div class="box-image" style="background-image: url('box4_image.jpg')"></div>
        <p>see more</p>
        </div></div>

        <div class="box1 box">
            <div class="box-content">
                <h2>Cosmetics</h2>
            <div class="box-image" style="background-image: url('box5_image.jpg')"></div>
            <p>see more</p>
            </div>    
        </div>
        <div class="box2 box"><div class="box-content">
            <h2>Pets</h2>
        <div class="box-image" style="background-image: url('box6_image.jpg')"></div>
        <p>see more</p>
        </div></div>
        <div class="box3 box"><div class="box-content">
            <h2>New Arrivals and Toys</h2>
        <div class="box-image" style="background-image: url('box7_image.jpg')"></div>
        <p>see more</p>
        </div></div>
        <div class="box4 box"><div class="box-content">
            <h2>Discover Fashion Trends</h2>
        <div class="box-image" style="background-image: url('box8_image.jpg')"></div>
        <p>see more</p>
        </div></div>

    </div>
    <footer>
        <div class="foot-panel">
            Back to Top
        </div>
        
        <div class="foot-panel2">
            <ul>
                <p>Get to know</p>
                <a>Careers</a>
                <a>Blogs</a>
                <a>About Amazon</a>
                <a>Investor Relations</a>
                <a>Amazon Devices</a>
                <a>Amazon Sciences</a>
            </ul>

            <ul>
                <p>Make Money with Us</p>
                <a>Sell products on Amazon</a>
                <a>Sell on Amazon Business</a>
                <a>Sell apps on Amazon</a>
                <a>Become an Affiliate</a>
                <a>Advertise Your Products</a>
                <a>Self-Publish with Us</a>
            </ul>

            <ul>
                <p>Amazon Payment Products</p>
                <a>Amazon Business Card</a>
                <a>Shop with Points</a>
                <a>Reload Your Balance</a>
                <a>Amazon Currency Converter</a>
            </ul>

            <ul>
                <p>Let Us Help You</p>
                <a>Amazon and COVID-19</a>
                <a>Your Account</a>
                <a>Your Orders</a>
                <a>Shipping Rates & Policies</a>
                <a>Returns & Replacements</a>
                <a>Help</a>
            </ul>
        </div>
        <div class="foot-panel3">
            <div class="logo"></div>
        </div>

        <div class="foot-panel4">
            <div class="pages">
                <a>Conditions of use</a>
                <a>Privacy Notices</a>
                <a>Your ads privacy choices</a>
            </div>
            <div class="copyright">© 1996-2023, Amazon.com, Inc. or its affiliates</div>
        </div>
    </footer>
</body>
</html>
