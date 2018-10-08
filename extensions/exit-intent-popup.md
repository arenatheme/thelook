### Apply Coupon Automaticaly Intent Popup Coupon to Product Page

Using 2 metafield following instruction: [Shopify Metafield name Bundle Product ](/shopify-metafield.md)

```
- namespace: c_f
- key: discount_code
- value: Add your Coupon code for the product

- namespace: c_f
- key: discount_percent
- value: Display percent of discount
```
![](/assets/metafieldproduct.png)

When navigate to Product page, add custom field for product page with Discount code & Discount percent detail.

The popup will show when people go to outside of the webpage (Intent Exit). If the customer click to apply, it's will auto apply the coupon code at checkout step.
**
![](/assets/thelook-intent-popup.png)

