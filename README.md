<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mobile Product Picker</title>
<style>
  /* Styles for the mobile product picker */
  #mobile-product-picker {
    display: none; /* Hidden by default */
    margin: 0 auto;
    padding: 0; /* Updated padding to 0 */
    max-width: 600px; /* Adjust the maximum width as needed */
  }
  #mobile-product-picker .product {
    width: calc(50% - 10px); /* Adjusted width to account for no outer spacing */
    margin: 5px; /* Reduced margin to minimize space between products */
    background-color: #fff; /* White background */
    border-radius: 10px; /* Rounded corners */
    overflow: hidden; /* Ensure content respects border radius */
    float: left; /* Float left to align two products side by side */
    box-sizing: border-box; /* Include padding and border in the element's total width and height */
    padding: 0; /* Ensure no padding inside the product container */
    text-align: center; /* Center-align content */
  }
  #mobile-product-picker .product img {
    width: 100%; /* Ensure the image fills the container width */
    height: auto; /* Adjust height automatically to maintain aspect ratio */
    object-fit: cover; /* Ensure the image covers the container fully */
    border-radius: 10px; /* Rounded corners */
    display: block; /* Ensure the image is displayed as a block to fill the container */
  }
  @media (max-width: 768px) {
    #mobile-product-picker {
      display: block; /* Show only on mobile */
    }
    #mobile-product-picker .product {
      width: calc(50% - 10px); /* Adjust width for mobile view */
      margin: 5px; /* Ensure minimal margin on mobile for a tighter layout */
    }
  }
</style>
</head>
<body>

<!-- Container for the mobile product picker -->
<div id="mobile-product-picker">
  <!-- Product 1 -->
  <a href="https://bbqarm.com.au/collections/kits" class="product">
    <img src="https://cdn.shopify.com/s/files/1/2093/3933/files/Untitled_design_-_2024-02-14T180640.793.png?v=1707898013" alt="Product 1">
  </a>
  <!-- Product 2 -->
  <a href="https://bbqarm.com.au/collections/bbqarm-acessories" class="product">
    <img src="https://cdn.shopify.com/s/files/1/2093/3933/files/Untitled_design_-_2024-02-14T180802.466.png?v=1707898097" alt="Product 2">
  </a>
  <!-- Product 3 -->
  <a href="https://bbqarm.com.au/collections/starlink" class="product">
    <img src="https://cdn.shopify.com/s/files/1/2093/3933/files/Untitled_design_-_2024-02-14T181005.280.png?v=1707898231" alt="Product 3">
  </a>
  <!-- Product 4 -->
  <a href="https://bbqarm.com.au/products/bbqarm-clothesline-connector-kit" class="product">
    <img src="https://cdn.shopify.com/s/files/1/2093/3933/files/Clothesline_Connector_Kit.png?v=1707797793" alt="Product 4">
  </a>
</div>

</body>
</html>
