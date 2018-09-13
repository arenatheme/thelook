****Shopify does not support input product custom fields in the dashboard, but there are some add-ons for this that you can use to improve product quality. 

Eg. Add a short description, video embedded, 3D product embed... for each product page. Add Sub collection for Collection page.


* One of the extensions you can refer to is the Custom Field Chrome extension made by Jason at [https://chrome.google.com/webstore/detail/custom-fields-for-shopify/alfplfpobekffinigeidgmmfjollghln](https://chrome.google.com/webstore/detail/custom-fields-for-shopify/alfplfpobekffinigeidgmmfjollghln). 

* Please refer to [the user manual](https://freakdesign-us.s3.amazonaws.com/shopify/custom_fields/freakdesign-custom-fields-for-shopify-guide.pdf)


1. Currently, **custom field extensions** only support **Chrome browser** so to use you must install this browser. [Download and install here](https://www.google.com/intl/en/chrome/browser/desktop/index.html)

2. Install Chrome Extension: ShopifyFD Dashboard Tool. [Download and install](https://chrome.google.com/webstore/detail/shopifyfd-dashboard-tool/lffljkleilfpjlmcdnoaghhcbnemelge)

3. **Download & Install Chrome Extension**: Custom Fields for Shopify
https://chrome.google.com/webstore/detail/custom-fields-for-shopify/alfplfpobekffinigeidgmmfjollghln

4. Add **New meta field** on the shop. 

    * From your Shopify admin, go to **Settings > General**
    * Click ** ShopifyFD Dashboard Icon** at Top Bar Chrome Browser.
    The Store Metafield will showup.
    ![](/assets/ShopifyFD.png)
    * **Add New Metafield** & **click Save**

    ![](https://media.giphy.com/media/xT9IgsIcmG9yPuYXXG/giphy.gif).

* There are fie Metafield data that we support.

**Collection Page**

**Product Page**

* _Short Description Meta Field_
    ```
    - namespace: c_f
    - key: description_excerpt
    - value: Add the product short description!
    ```

* _Video Meta Field_
    ```
    - namespace: c_f
    - key: video_url
    - value: Add your amazing video!
    ```

Size Chart Meta Field:

```
- namespace: c_f
- key: size_chart
- value: Add your image size chart url!
```

```
Image 360 Meta Field:

- namespace: c_f
- key: image360
- value: Add your image url!

```

** Bundle Product Meta Field **

```
- namespace: c_f
- key: bundle_1
- value: Add your product handle #1!

- namespace: c_f
- key: bundle_2
- value: Add your product handle #2!
```


```

Size Chart Meta Field:

- namespace: c_f
- key: size_chart
- value: Add your image size chart URL!

```


