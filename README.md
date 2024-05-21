# Amazon-Clone-Project
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content=
"width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <!-- Font Awesome CDN -->
    <link rel="stylesheet" href=
"https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" integrity=
"sha512-DTOQO9RWCH3ppGqcWaEA1BIZOC6xxalwEsw9c2QQeAIftl+Vegovlnee1c9QX4TctnWMn13TZye+giMm8e2LwA=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <title>Amazon Clone</title>
</head>

<body>
    <header>
        <nav>
            <div class="nav-left">
                <div class="nav-logo">
                    <img src=
"https://i0.wp.com/www.dafontfree.co/wp-content/uploads/2021/11/Amazon-Logo-Font-1-scaled.jpg?resize=2560%2C1578">
                </div>
                <div class="location">
                    <p class="top-text">Deliver to</p>
                    <div class="location-icon">
                        <i class="fa-solid fa-location-dot"></i>
                        <p class="bottom-text">India</p>
                    </div>
                </div>
            </div>

            <div class="nav-center">
                <select class="search-dropdown">
                    <option>All</option>
                    <option>All Departments</option>
                    <option>Arts & Crafts</option>
                </select>
                <input type="text" placeholder="Search Amazon" 
                    class="search-box">
                <div class="search-icon">
                    <i class="fa-solid fa-magnifying-glass" 
                        style="color: #28416c;">
                    </i>
                </div>
            </div>

            <div class="nav-right">
                <div class="language-option">
                    <div class="flag">
                        <i class="fa-regular fa-flag"></i>
                    </div>
                    <select class="select-language">
                        <option value="lan">EN</option>
                        <option value="lan">ES</option>
                        <option value="lan">AR</option>
                    </select>
                </div>

                <div class="account-option">
                    <p class="top-text">
                        Hello, sign in
                    </p>
                    <select class="select-account">
                        <option value="Account">
                            Account & Lists
                        </option>
                        <option value="Account">
                            Account & Lists
                        </option>
                        <option value="Account">
                            Account & Lists
                        </option>
                    </select>
                </div>

                <div class="order-option">
                    <p class="top-text">
                        Returns
                    </p>
                    <p class="bottom-text">
                        & Orders
                    </p>
                </div>

                <div class="cart-option">
                    <div class="cart-logo">
                        <i class="fa-solid fa-cart-shopping"></i>
                    </div>
                    Cart
                </div>
            </div>
        </nav>

        <div class="nav-options">
            <div class="all-logo">
                <i class="fa-solid fa-bars"></i>
                <p class="list">All</p>
            </div>

            <div class="options">
                <p>Today's Deals</p>
                <p>Customer Service</p>
                <p>Registry</p>
                <p>Gift Cards</p>
                <p> Sell</p>
            </div>
        </div>
    </header>

    <main>
        <div class="carousel">
            <div class="slides-container">
                <div id="slide1" class="slide">
                    <div class="content">
                        <img src=
"https://m.media-amazon.com/images/I/61zAjw4bqPL._SX3000_.jpg">
                    </div>
                    <a href="#slide3" class="prev arrow">
                        <i class="fa-solid fa-chevron-left" 
                            style="color: #ffffff;">
                        </i>
                    </a>
                    <a href="#slide2" class="next arrow">
                        <i class="fa-solid fa-chevron-right" 
                            style="color: #ffffff;">
                        </i>
                    </a>
                </div>
                <div id="slide2" class="slide">
                    <div class="content">
                        <img src=
"https://images-eu.ssl-images-amazon.com/images/G/31/img22/march/brands/GW/Under_1499_Tallhero_3000x1200._CB561212093_.jpg">
                    </div>
                    <div class="arrows"></div>
                    <a href="#slide1" class="prev arrow">
                        <i class="fa-solid fa-chevron-left" 
                            style="color: #ffffff;">
                        </i>
                    </a>
                    <a href="#slide3" class="next arrow">
                        <i class="fa-solid fa-chevron-right" 
                            style="color: #ffffff;">
                        </i>
                    </a>
                </div>
                <div id="slide3" class="slide">
                    <div class="content">
                        <img src=
"https://m.media-amazon.com/images/I/71Ie3JXGfVL._SX3000_.jpg">
                    </div>
                    <div class="arrows"></div>
                    <a href="#slide2" class="prev arrow">
                        <i class="fa-solid fa-chevron-left" 
                            style="color: #ffffff;">
                        </i>
                    </a>
                    <a href="#slide1" class="next arrow">
                        <i class="fa-solid fa-chevron-right" 
                            style="color: #ffffff;">
                        </i>
                    </a>
                </div>
            </div>
            <div class="text">
                <p>
                    You are on amazon.com. You can also shop 
                    on Amazon India for millions of products 
                    with fast local delivery. 
                    <a href="#"> 
                        Click here to go to amazon.in
                    </a>
                </p>
            </div>
        </div>

        <div class="items-container">
            <div class="item-card">
                <h2>Gaming accessories</h2>
                <img src=
"https://th.bing.com/th/id/OIP.mHrpzos9xo4pDxF0qsEb8QAAAA?w=374&h=175&c=7&r=0&o=5&dpr=1.3&pid=1.7">
                <p>
                    <a href="#">See more</a>
                </p>
            </div>
            <div class="item-card">
                <h2>Deal in PCs</h2>
                <img src=
"https://images-na.ssl-images-amazon.com/images/G/01/AmazonExports/Events/2023/EBF23/Fuji_Desktop_Single_image_EBF_1x_v1._SY304_CB573698005_.jpg">
                <p>
                    <a href="#">See more</a>
                </p>
            </div>
            <div class="item-card">
                <h2>Amazon Gadget Store</h2>
                <img src=
"https://th.bing.com/th/id/OIP.bIGquh448SYk452aqnHn6QAAAA?w=274&h=180&c=7&r=0&o=5&dpr=1.3&pid=1.7">
                <p>
                    <a href="#">See more</a>
                </p>
            </div>
            <div class="item-card">
                <h2>Handpicked music</h2>
                <img src=
"https://cdn.gearnews.com/wp-content/uploads/2023/01/cr-01-1536x848.jpg">
                <p>
                    <a href="#">See more</a>
                </p>
            </div>
            <div class="item-card">
                <h2>Fill your Easter basket</h2>
                <img src=
"https://th.bing.com/th/id/OIP._Kv7xIHUfVn45jm9VVxtFwHaE8?rs=1&pid=ImgDetMain">
                <p>
                    <a href="#">See more</a>
                </p>
            </div>
            <div class="item-card">
                <h2>Top Deal</h2>
                <img src=
"https://media.allure.com/photos/58f77989f39db96647dbce31/master/pass/edsfaves-041017-lede.jpg">
                <p>
                    <a href="#">See more</a>
                </p>
            </div>
            <div class="item-card">
                <h2>Shop deals in Fashion</h2>
                <img src=
"https://th.bing.com/th/id/OIP.NAzI6q1rrkLsr2kNO7ZMIgHaJc?rs=1&pid=ImgDetMain">
                <p>
                    <a href="#">See more</a>
                </p>
            </div>
            <div class="item-card">
                <h2>Gaming merchandise</h2>
                <img src=
"https://th.bing.com/th/id/OIP.3lOpkfdIx8GieLGleegkcwHaDt?w=435&h=174&c=7&r=0&o=5&dpr=1.3&pid=1.7">
                <p>
                    <a href="#">See more</a>
                </p>
            </div>
            <div class="item-card">
                <h2>Movies</h2>
                <img src=
"https://www.georgiasbdc.org/wp-content/uploads/2022/06/Film-Class.jpg">
                <p>
                    <a href="#">See more</a>
                </p>
            </div>

        </div>
    </main>

    <footer>
        <a href="#" class="back-option">
            Back to top
        </a>

        <div class="footer-links">
            <ul>
                <p>Get to Know Us</p>
                <a>Careers</a>
                <a>Blog</a>
                <a>About Amazon</a>
                <a>Investor Relations</a>
                <a>Amazon Devices</a>
                <a>Amazon Science</a>
            </ul>
            <ul>
                <p>Make Money with Us</p>
                <a>Sell products on Amazon</a>
                <a>Sell on Amazon Business</a>
                <a>Sell apps on Amazon</a>
                <a>Become an Affiliate</a>
                <a>Self-Publish with Us</a>
                <a>Host an Amazon Hub</a>
                <a>›See More Make Money with Us</a>
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
                <a>Manage Your Content and Devices</a>
                <a>Amazon Assistant</a>
                <a>Help</a>
            </ul>
        </div>
        <div class="country-info">
            <div class="logo">
                <img src=
"https://i0.wp.com/www.dafontfree.co/wp-content/uploads/2021/11/Amazon-Logo-Font-1-scaled.jpg?resize=2560%2C1578">
            </div>
            <div class="options">
                <select>
                    <option value="En">
                        English
                    </option>
                </select>
                <select>
                    <option value="1">
                        $ USD - U.S. Dollar
                    </option>
                </select>

                <select>
                    <option value="4"> 
                        United states
                    </option>
                </select>
            </div>
        </div>
        <div class="policies">
            <div class="pages">
                <a href="#">Conditions of Use</a>
                <a href="#">Privacy Notice</a>
                <a href="#">Your Ads Privacy Choices</a>
            </div>
            © 1996-2023, Amazon.com, Inc. or its affiliates
        </div>
    </footer>
</body>

</html>
