# WooCommerce-insertion

In this example I added the javascript, style, and html to make a custom checkout cart and also not have this clash with the built-in global css from the WordPress and WooCommerce settings. You can just plug this in as is (not prettiest solution, but very portable and easy for a non-programmer to just copy and paster with Elementor!)

Since every cart action is stored in localSstorage API, you just override the add to cart function in cart.php to accept these (or make an ajax call to your apecific add-to-cart endpoint) and then you're done!
