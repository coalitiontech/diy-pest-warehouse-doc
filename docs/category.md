# Category Page
The category page lists all the products in the category.

## Banner
![category-banner.png](img/category-banner.png)

Navigate to <a href="https://store-lr0iyiahf7.mybigcommerce.com/manage/products/categories">category section</a> on the bigcommerce dashboard, and select the category to edit:

![category-edit.png](img/category-edit.png)

### Category Title

Display name of the category is the category title, change it by editing following marked area:

![category-edit-title.png](img/category-edit-title.png)

### Category Description

Click the below marked area to open the source code area of the section:

![category-edit-desc-source.png](img/category-edit-desc-source.png)

Everything <strong>before</strong> the (```<!-- split -->```) seperator counts as the description of the page, we had to do that because of the migration purposes:

![category-edit-desc-source-split.png](img/category-edit-desc-source-split.png)

To edit the existing category description, directly edit the part <strong>before</strong> seperator and please make sure the split seperator is as shown in the image and click save buttons.

To add description in the category, then add a description first and end it by adding (```<!-- split -->```), and that will add the description. If  there is already content in it, still first add the description followed by the split seperator and then keep the remaining content as is and click save buttons.

### Category Image

Scroll of the category image section:

![category-edit-image.png](img/category-edit-image.png)

Click the three dots to change or delete category banner image.

Save to publish changes.

## Title and Description
It contains the category name and description.

We used the built-in BigCommerce category settings for this.

To edit it, go to the category settings in BigCommerce.

## Filters
The filters are used to filter the products based on the price, brand, and other custom fields.

We used the built-in BigCommerce filters and custom fields for this.

You can see all the available filters going to the 'Filtering' settings in BigCommerce by selecting 'All filters'. You can then select the filters you want to show on the category page.

For more information about the filters, see the <a href="https://support.bigcommerce.com/s/article/Product-Filtering-Settings" target="_blank">BigCommerce documentation</a>.

## Products
It lists all the products in the category.

## FAQ
![category-faq.png](img/category-faq.png)

Copy the following snippet:

```html
<div class="custom-accordion">
    <h3>How do I know if I have a bed bug infestation?</h3>
</div>
<div class="panel">
    <div class="panel-inner">
        <div>
            <p>Bed bug infestations can be hard to spot early. Common signs include waking up with red, itchy bites, often in straight lines or clusters. Look for reddish-brown stains on mattresses or bedding, which may result from crushed bugs or droppings. You might also notice tiny black spots, bed bug feces, or shed skins near mattress seams, box springs, or bed frames. Check these areas with a flashlight, as bed bugs hide in crevices and cracks. Catching infestations early makes them easier to treat effectively.</p>
        </div>
    </div>
</div>

<div class="custom-accordion">
    <h3>What are the best products to treat a bed bug infestation?</h3>
</div>
<div class="panel">
    <div class="panel-inner">
        <div>
            <p>The most effective solution combines multiple products. Bed bug sprays with pyrethrins or pyrethroids kill bed bugs instantly on visible surfaces. Bed bug insecticide dusts are ideal for hidden spaces like wall voids or furniture cracks, providing long-term results. Insect growth regulators (IGRs) help prevent the bugs from reproducing, breaking the infestation cycle. Mattress encasements are also valuable—they trap bed bugs and protect against future infestations. To maximize effectiveness, follow product instructions precisely.</p> 
        </div>
    </div>
</div>

<div class="custom-accordion">
    <h3>Are bed bug treatments safe for pets and children?</h3>
</div>
<div class="panel">
    <div class="panel-inner">
        <div>
            <p>Bed bug treatments can be safe for households if applied properly. Keep pets and children away from treated areas until the product has dried completely. Ensure proper ventilation during and after application. For added safety, botanical or natural-based bed bug killer products are a good alternative though they may not be as effective. Always read product labels carefully and follow guidelines to avoid risks. If unsure about how to use bed bug insecticides, consult a professional pest control expert.</p>
        </div>
    </div>
</div>

<div class="custom-accordion">
    <h3>How long does it take for bed bug treatments to work?</h3>
</div>
<div class="panel">
    <div class="panel-inner">
        <div>
            <p>Treatment duration depends on the severity of the infestation and the thoroughness of your approach. Some sprays kill bed bugs immediately, while others require follow-ups. Expect to repeat treatments every 10–14 days to catch newly hatched bugs. Complete eradication often takes several weeks with consistent application.</p>
        </div>
    </div>
</div>

<div class="custom-accordion">
    <h3>How do I prevent a bed bug infestation in my home?</h3>
</div>
<div class="panel">
    <div class="panel-inner">
        <div>
            <p>Prevention is key to avoiding infestations. Regularly inspect your bedding, especially after traveling. When staying in hotels, check the room for signs of bed bugs before unpacking, and store luggage off the floor. Use mattress encasements and vacuum frequently, focusing on furniture seams and cracks. Avoid bringing in untreated second-hand furniture. With consistent habits and knowledge of how to effectively use bed bug insecticides, you can significantly reduce the risk of infestations.</p> 
        </div>
    </div>
</div>
```

```json
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What are the best products to treat a flea infestation?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "To address a flea problem effectively, you can use a combination of sprays, powders, foggers, and insect growth regulators (IGRs). Sprays and foggers target adult pests instantly, while IGRs work by halting the development of eggs and larvae. Powders are particularly useful in crevices and under furniture. Treating multiple surfaces like carpets, pet bedding, and upholstery ensures that fleas are eliminated from every stage of their life cycle."
      }
    },
    {
      "@type": "Question",
      "name": "What’s the difference between flea sprays, powders, and foggers?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Each flea killer option has its strengths depending on the infestation. Indoor flea sprays are adaptable and work well on soft furnishings and other surfaces. Powders are better suited for getting into cracks or deep layers of carpets. Foggers, on the other hand, disperse treatments throughout an entire room, even reaching difficult-to-access areas. A combination of these methods can give you the most thorough results."
      }
    },
    {
      "@type": "Question",
      "name": "Can I use flea sprays on furniture, carpets, and bedding?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Most sprays are formulated for luxe on household fabrics, but checking the product label is crucial. Many are designed to kill pests hiding in upholstery, rugs, and linens while being safe for these surfaces. Be sure to apply these types of flea killers as instructed and allow the areas to dry before making contact. Following the proper guidelines ensures both safety and effectiveness."
      }
    },
    {
      "@type": "Question",
      "name": "How long does it take for flea treatments to work?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "The time frame varies with each pest control product for fleas. Some sprays and foggers act immediately on adult fleas, but eradicating eggs and larvae may require days or weeks. Using complementary products, such as IGRs or flea insecticides, can accelerate this process by disrupting their growth cycle. Consistency in treatment and cleaning is key for long-term success."
      }
    },
    {
      "@type": "Question",
      "name": "How often should I apply flea treatments to my home?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "For a severe infestation, treating the space every two weeks is effective until all activity has stopped. Afterward, applying flea killer treatments every six to eight weeks helps maintain a pest-free home. In addition to these steps, regular cleaning of items like bedding and rugs can further prevent re-infestation."
      }
    }
  ]
}
```

Replace the content and paste it in the following section of the metafield app:

Navigate to Metafield app through this <a href="https://store-lr0iyiahf7.mybigcommerce.com/manage/app/39776">link</a>.

![category-faq-metafield-main.png](img/category-faq-metafield-main.png)

Select the category from category dropdown as marked below:

![category-faq-metafield-list.png](img/category-faq-metafield-list.png)

Replace or edit the part of the HTML in below section:

![category-faq-metafield-list-html.png](img/category-faq-metafield-list-html.png)

Replace or edit the part of the Schema in below section and save the changes:

![category-faq-metafield-list-schema-save.png](img/category-faq-metafield-list-schema-save.png)

## Copy
![category-copy.png](img/category-copy.png)

Copy the following snippet:

```html
<div class="info-row">
    <div class="info-flex-first-column">
        <h2>Professional-Grade Bed Bug Insecticides</h2>
        <p>When untreated, <a href="https://www.diypestwarehouse.com/blogs/our-blog/your-ultimate-guide-on-how-to-get-rid-of-bed-bugs-fast">bed bug infestations</a> can be costly and difficult to eradicate. It's important that you start bed bug control as soon as possible, or else the situation will only worsen. The good news is DIY Pest Warehouse brings you everything you need to combat a bed bug infestation. These include professional-grade insecticide concentrates, <a href="https://www.diypestwarehouse.com/collections/bed-bug-aerosol-sprays">aerosol bed bug sprays</a>, insect growth regulators, and granules. Find the perfect bed bug killer products for you today.</p>
    </div>
    <div class="info-flex-second-column">
        <h2>DIY Solutions From Industry Experts</h2>
        <p>Bed bugs are hardy pests that can be difficult to kill, but <a href="https://www.diypestwarehouse.com/">DIY Pest Warehouse</a> brings bed bug control within your reach with the right combination of products. Our professional-grade bed bug eradication products are cheaper than an exterminator. Save up to 80% compared with exterminator costs with proven bed bug insecticides from the same trusted brands that professional exterminators use. Don't let bed bugs take over your home.</p>
    </div>
</div>
<div class="pests-stop-info">
    <h2>Stop Bugs Bugging You</h2>
    <p>Shop all your <a href="https://www.diypestwarehouse.com/collections">pest control products</a> at DIY Pest Warehouse. Our bed bug insecticides offer complete coverage for your home, office, and car to help you stop bugs from bugging you. Order now and enjoy fast, free shipping in the U.S. Need help? <a href="https://www.diypestwarehouse.com/pages/contact-us">Contact us</a> now.</p>
</div>
```
and paste it <strong>after</strong> the (```<!-- split -->```) seperator as previously was used for description in category banner <a href="#category-description">here</a>. Incase if there is no split seperator then you can add one before the pasted snippet code.

![category-copy-source.png](img/category-copy-source.png)

Change the content of the copied snippet code (please refer to the image displayed <a href="#copy">here</a>) and click the save buttons.