## Adding Requirement Shopify Metafield to your store.

Shopify metafields can help you extend the functionality of online shops by giving you the ability to store additional information on products, collections, orders, blogs, and pages.

Eg. Add a short description, video embedded, 3D product embed... for each product page. Add Sub collection for Collection page.

* One of the extensions you can refer to is the Custom Field Chrome extension made by Jason at [https://chrome.google.com/webstore/detail/custom-fields-for-shopify/alfplfpobekffinigeidgmmfjollghln](https://chrome.google.com/webstore/detail/custom-fields-for-shopify/alfplfpobekffinigeidgmmfjollghln).

* Please refer to [the user manual](https://freakdesign-us.s3.amazonaws.com/shopify/custom_fields/freakdesign-custom-fields-for-shopify-guide.pdf)

---

### Adding supported Meta field for Electro Theme

1. Currently, **custom field extensions** only support **Chrome browser** so to use you must install this browser. [Download and install here](https://www.google.com/intl/en/chrome/browser/desktop/index.html)

2. Download & Install [**ShopifyFD Dashboard Tool Chrome Extension**](https://chrome.google.com/webstore/detail/shopifyfd-dashboard-tool/lffljkleilfpjlmcdnoaghhcbnemelge?hl=en)

3. Add **New meta field** on the shop.

   * From your Shopify admin, go to **Settings &gt; General**
   * Click ** ShopifyFD Dashboard Icon** at Top Bar Chrome Browser.
     The Store Metafield will showup.
     ![](/assets/ShopifyFD.png)
   * **Add New Metafield** & **click Save**
     ![](https://media.giphy.com/media/xT9IgsIcmG9yPuYXXG/giphy.gif).

4. List of **Meta field** Electro support use  
   ![](/assets/metafield.png)

**Collection Page**

* _**New: Add Sub-collection**_

```
    - namespace: c_f
    - key: subcategory
    - value: Add menu handle item to display subcategory
```

**Product Page**

* _**New: Add Bundle Product**_

  ```
    - namespace: c_f
    - key: bundle_1
    - value: Add your product handle #1!

    - namespace: c_f
    - key: bundle_2
    - value: Add your product handle #2!
  ```

* _**New: Add Exit Intent Popup Product**_

  ```
    - namespace: c_f
    - key: discount_code
    - value: Add your Coupon code for the product

    - namespace: c_f
    - key: discount_percent
    - value: Display percent of discount
  ```

* _Add Countdount Timer_

  ```
    - namespace: c_f
    - key: bundle_1
    - value: Add your product handle #1!

    - namespace: c_f
    - key: bundle_2
    - value: Add your product handle #2!
  ```

* _Add Short Description_

  ```
    - namespace: c_f
    - key: description_excerpt
    - value: Add the product short description!
  ```

* _Add Product Image 360 Description_

```
    - namespace: c_f
    - key: image360
    - value: Add your image url!
```

* _Add Product Video Description_
  ```
    - namespace: c_f
    - key: video_url
    - value: Add your amazing video!
  ```
* _Add Size Chart_
  ```
    - namespace: c_f
    - key: image_size_chart
    - value: Add your image size chart url!
  ```

  **It's ready to use to add Custom Field for the Theme**

---

**Using Custom field to add content with Metafield**

1. Download & Install [**Custom Fields for Shopify** **Chrome Extension**](https://chrome.google.com/webstore/detail/custom-fields-for-shopify/alfplfpobekffinigeidgmmfjollghln?hl=en-GB)

This extension will help Shopify store owners edit content easier by using Custom Fields.





