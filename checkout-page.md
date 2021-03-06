# Checkout page

* [Adding to cart](#-adding-to-cartv)
* [List of items](#-list-of-items)
* [Shipping, billing](#-shipping-billing)
* [Review order](#-review-order)

In this manual you will find info how checkout page works from user perspective. It covers all user workflow from adding goods to shopping cart to paying and review order.

##<a id='adding-to-cart'></a> Adding to cart

While user surfing the site he can follow from home page to event pages, categories, shop and item pages. He can click 'Add to cart' button from any of theses pages and this item will appear in his shopping cart. There is specific for each item timeout during which item will be kept in cart. After this timeout item will be automatically removed from user shopping cart.

##<a id='list-of-items'></a> List of items
On all pages in user menu we have "Shopping bag" link. When user click it - we show list of items in his cart with all additional info related to items: Quantity, Image of item, Description (with links to full description), Expire time, Price and Total sum.

User can remove item, change quantity. Also he can uncheck items that he don't want to pay for right now. 

On the page we show help information (with ? mark) about "Return policy", "Shipping rules", "FAQ". Also at the bottom we have "Free shipping checklist" block, which indicates what user need to do for Free shipping: "Spend at least $99 on your purchase", "Sign up to receive our Daily Emails".

User can add Coupon code and apply it. Price total is automatically recalculated. Coupons affect Taxes but don't affect Shipping price.

##<a id='shipping-billing'></a> Shipping, billing
On this page user enters his billing and shipping address. When shipping and billing info was entered before, in previous session - we just populate info from database. User can ship items to the "billing addres" just checking box "Same as Billing". We have "Free shipping checklist" block on this page as well.

##<a id='review-order'></a> Review order
After user clicked Checkout button on "Shipping, billing page" - we send all info to server, process payment and shows him review.

Here he can see all info from previous pages he entered and track order. Tracking order also is available from User menu, "Orders".