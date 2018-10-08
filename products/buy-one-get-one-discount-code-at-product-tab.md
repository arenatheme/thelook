### BUY X GET Y COUPON

Using 5 metafields following instruction: [Shopify Metafield name Bundle Product ](/shopify-metafield.md)

```
- namespace: c_f
- key: buy_x_get_y
- value: DISCOUNTED VALUE: Discount percent

- namespace: c_f
- key: product_y
- value: Product Y Handle

- namespace: c_f
- key: discount_code_x_y
- value: discount code buy x get y

- namespace: c_f
- key: number_discount_x
- value: Quantity product X customer buy to apply Buy X get Y Coupon

- namespace: c_f
- key: number_discount_y
- value: Quantity product Y customer gets when apply Buy X get Y Coupon

```

Eg. If you would like to apply Coupon Code with detail following setup:

- Discount code: xyz
- Discount type: Buy X Get Y
- Customer buys: 2 ALPHADOM PRODUCT SAMPLE product with product handle alphadom-product-sample -> Product X
- Customer gets: 3 Black Fashion Zapda Shoes product with product handle black-fashion-zapda-shoes
- AT A DISCOUNTED VALUE: 70%



When navigate to Product page, add custom field for product page with Discount code & Discount percent detail.

The popup will show when people go to outside of the webpage (Intent Exit). If the customer click to apply, it's will auto apply the coupon code at checkout step.
**
![](/assets/intentpopup.png)


