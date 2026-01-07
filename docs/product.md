# Product Page
The product page displays the information about the product. It includes the product name, description, price, options, and an image of the product.

Most of the product page is built with the default BigCommerce settings, for more information regarding how to add a product in Bigcommerce with the V2 settings, refer to this <a href="https://support.bigcommerce.com/s/article/Adding-Products-v2?language=en_US" target="_blank">documentation</a>. 

There are some parts on the product page that need to follow specific guidelines.

## Short Description


The short description is a brief description of the product. It should be a short paragraph that describes the product in a few sentences. The short description should be displayed at the top of the product page.
It is not mandatory, so not all the products will have it.

## Custom Product tabs
![pdp-custom-tab.png](img/pdp-custom-tab.png)

### Overview Tab
![pdp-custom-tab-overview.png](img/pdp-custom-tab-overview.png)

Navigate to <a href="https://store-lr0iyiahf7.mybigcommerce.com/manage/products">product section</a> on the bigcommerce dashboard, and select the product to edit:

![pdp-custom-tab-bc-view.png](img/pdp-custom-tab-bc-view.png)

Click the Description tab in product page:

![pdp-custom-tab-bc-description-tab.png](img/pdp-custom-tab-bc-description-tab.png)

Content added on the following section will be displayed under Overview tab:

![pdp-custom-tab-bc-description.png](img/pdp-custom-tab-bc-description.png)

### Product Data Sheet Tab

![pdp-custom-tab-data-sheet.png](img/pdp-custom-tab-data-sheet.png)

Coming soon...

### Product Specific Table Tab

![pdp-custom-tab-specific-table.png](img/pdp-custom-tab-specific-table.png)

Copy the following code snippet and replace the content between the start and end tag:

```html
<div class="halo-custom-tab" data-custom-tab="Product Specifications Table">

    <!-- Remove below content and replace it with your content - Starts here -->
    <p>Damus de ullamcorper neque. Sed vitae mi a mi pretium aliquet an sed helito. Pellentesque nulla eros accumsan quis justo at tincidunto, de drostique des commodo pharetras retium.</p>
    <div class="scrollable-wrapper">
        <table>
            <tbody>
                <tr>
                    <td class="tb-title">Comodous</td>
                    <td>Comodous in tempor ullamcorper miaculis</td>
                </tr>
                <tr>
                    <td class="tb-title">Posuere</td>
                    <td>Nam tempus turpis at metus scelerisque placerat nulla deumantos solicitud felis</td>
                </tr>
                <tr>
                    <td class="tb-title">Divamus</td>
                    <td>Pellentesque vitae neque mollis durna mattis loreto</td>
                </tr>
                <tr>
                    <td class="tb-title">Molestie</td>
                    <td>Donec pretium egestas sapien et mollis</td>
                </tr>
                <tr>
                    <td class="tb-title">Milancelos</td>
                    <td>Proin molestie egestas morci de suscipit risus posuere lorem</td>
                </tr>
                <tr>
                    <td class="tb-title">Cosmopolis</td>
                    <td>Pellentesque diam dolor, elementum etos lobortis des mollis</td>
                </tr>
            </tbody>
        </table>
    </div>
    <!-- End here -->
</div>
```
To change tab title replace (``` Product Specifications Table ```) in (``` data-custom-tab="Product Specifications Table" ```) with your desired title in above copied snippet code.

![pdp-custom-tab-specific-table-bc.png](img/pdp-custom-tab-specific-table-bc.png)

Navigate back to the description tab as previously did on <a href="#overview-tab">Overview tab</a>, 

![pdp-custom-tab-specific-table-bc-paste.png](img/pdp-custom-tab-specific-table-bc-paste.png)

Paste the code right after the description added for the overview tab. If there is no content paste it directly in the empty space.

Click Ok and Save to publish.

## FAQ
![pdp-faq.png](img/pdp-faq.png)

Coming Soon...

## Related Items or You May Also Like

The related items section displays products that are related to the current product. These are usually automatically picked by BigCommerce or can be set manually in the product settings.
Please refer to the BigCommerce <a href="https://support.bigcommerce.com/s/article/Adding-Products-v2?language=en_US#related" target="_blank">documentation</a> for more details.
