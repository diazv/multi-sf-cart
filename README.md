# Cornerstone
This uses the base Cornerstone theme to create a custom page which uses a modified product-view to display a "Multi" button for placeholder bundle products (this uses the Storefront Cart API to add to cart), and Stencil Utils to retrieve intended product info. To apply this to a product on your store you'll need to include the custom field "is_bundled" with a value of true, as well as "foo" with the value for any Product ID you want added to cart and displayed on the page. Then apply the "multi-layout.html" custom template to that product.
