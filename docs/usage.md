# Usage Guide

## Get Started

Thanks for using our theme!

To set up the theme exactly like our demo stores, you may need to install the our free app **[PapaThemes Widgets](https://www.bigcommerce.com/apps/papathemes-widgets/)**. This app provides additional widgets to build the content in Page Builder visually without coding skill. 

For displaying your Instagram photos on your website, you can use our free tool **[PapaThemes Instagram](https://instagram.papathemes.com/)**. We will guide you step by step later in this manual.

### Customizing Typography, Fonts and Colors

Customizing Typography, Fonts and Colors, Buttons in **Page Builder** > **Theme Styles** > **General**. There are dozens of options to help you customize your website beautifully and uniquely.

### Customizing Checkout Page's Typography and Colors

Customizing the checkout page's typography and colors in **Page Builder** > **Theme Styles** > **Optimized Checkout**

### Installing PapaThemes Widgets App

Find and install **[PapaThemes Widgets](https://www.bigcommerce.com/apps/papathemes-widgets/)** app from [BigCommerce Apps Marketplace](https://www.bigcommerce.com/apps/).

After installed, go to your admin page, on the left sidebar, click **Apps** >** My Apps**, click **Launch** button of PapaThemes Widgets app to open the app:

![launch-papathemes-widgets-app](img/launch-papathemes-widgets-app.jpg)

Then click the Install buttons in turn to install all available widgets:

![install-papathemes-widgets](img/install-papathemes-widgets.jpg)

Go to **Storefront** > **My Themes** > click **Customize** in dropdown menu of Dinosaur theme to open Page Builder. Select any theme style to start:

![click-theme-customize](img/click-theme-customize.jpg)

Verify the widgets installed successfully if they appear in Page Builder:

![custom-widgets-appear](img/custom-widgets-appear.jpg)


## Setting Up Man Style Home Page

To start customizing the theme, login to your admin panel, go to **Storefront** > **My Themes**, click **Customize** button next to theme thumbnail.

### Multistore guide

![multi-store-after](img/multi-store-after.jpg)

To display the multistore guide on top header, drag and drop the HTML widget to the corresponding position, paste the given code below to the HTML editor, then click Save HTML button.

```html
<div class="header-multi-storefront">
<a href="/bath/">Shop Kid</a>
<a class="active-page">Shop Men</a>
<a href="/kitchen/">Shop Women</a>
</div>

```

![multi-store-guide](img/multi-store-guide.jpg)

### Header

![Header](img/header.jpg)


To configure the header, click on **Theme Styles** > **Header** section, here you can config the header colors, store logo position and size.

**User Navigation** allows to change colors of the icon phone, cart.

**Top Bar** section allows to change color of this top bar.

**Watch the instruction video:**

<iframe width="760" height="515" src="https://www.youtube.com/embed/Ry8ANybgdSI?si=ZIJXrTKBdDY4IXn4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

To edit the background of the top header, click on Theme **Styles** > **Header**. Dinosaur theme provides users with three options to change the background by modifying the **Background Image Link** field as shown below:

- `blank`: leave the field empty, the background will be specified follow **Background color** field.

![blank-bg-img](img/blank-bg-img.jpg)

- `default`: Top header will use the default image of the theme to set as background header.

![default-bg-img](img/default-bg-img.jpg)

- `link`: Top header will be the link you provided in the input to set the background.

![link-bg-img](img/link-bg-img.jpg)

#### Quick search

**Quick Search** allows user to change the colors of the search form.

To configure the **Quick Search**, click on **Theme Styles** > **Header**. In **Quick Search** section you can change text colors, hover, border, and background of the search field.

To change popular search keywords, type your text in **popular search keywords** field as picture below.

![header-quick-search](img/quick-search.jpg)
#### Main Navigation

**Main Navigation** allows to customize this navigation bar like changing the menu type to column, dropdown menu or mega menu; changing colors of the top menu as well as the sub-menus. There is an option "**Hide webpage links**" that allows to hide the static web page links on the main navigation.

To configure the Main navigation, click on **Theme Styles** > **Header**. In **Main navigation** section you can change:

- **Root menu item color**: text color of root menu item.

- **+ Hover**: text color on hover on the root menu item.

- **+ Background**: background color of sub menu block.

- **+ Border color**: border-color bottom of main navigation.

- **Sub menu item color**: text color of the submenu item.

- **+ Hover**: text color on hover on the submenu item.

- **+ Background**: background color of the submenu item.

![main-navigation](img/main-navigation.jpg)

To config style of main navigation, click on **Theme Styles** > **Header**. In **Main navigation** select **Menu style**. The theme offer 3 option as below:

- `Mega menu`: show submenu under Mega menu style. **Mega menu** allow user insert banner and product into it

![mega-menu](img/mega-menu.jpg)

- `Dropdown`: show sub-menu item as dropdown style.

![dropdown-menu](img/dropdown-menu.jpg)

- `Column`: show sub-menu item as column style.

![column-menu](img/column-menu.jpg)

To create banner on Megamenu, in **Header** find and checked **Show widgets in mega menu** to show **edit menu widget** button.

Click on **edit menu widget** button to open Mega menu in design mode.

![edit-widget-megamenu](img/edit-widget-button.jpg)


#### Hide webpage links

To hide Weboage links such as **Contact us**, **About Us**, **Shipping and return** from header, in **Themes style** > **Header** Find **Hide Webpage links** option checked to hide all the links except **Categories** link.

If you only want to hide some specific links not all the link you can do following step:

- `+ Begining` field: input the order link you want to show.
- `+ Limit` field: input number web link you want to show after begining field.

For example: if you only want show **Theme Features** and **shipping & return**:
- Begining field: 2;
- limit field:  2;

Note: the order will only count non-categories link.

Before:

![web-links-order](img/web-links-order.jpg)

Affer:

![hidden-web-links](img/hidden-web-links.jpg)

### Top Banner

Go back to **Storefront** > **My Themes** > click **Customize** button beside the theme thumbnail. You can see the top banner appears above the header. To change the colors of the top banner, go to **Theme Styles** > **General** > **Top banners** section. Here you can change the text color and the background color.

**Watch the instruction video:**

<iframe width="760" height="515" src="https://www.youtube.com/embed/yvkQCvDx3Fc?si=WJek4U1BstkN2sFU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


You can also create **top banner** by drag and drop **HTML widget** into corresponding position:

![top-banner](img/top-banner.jpg)

Enter your content inside `<p></p>`.

```html
<p>Get a discount with our limited time offer - Use code&nbsp;<strong>SAVE10</strong>&nbsp;for&nbsp;<strong>10%</strong>&nbsp;off your purchase!</p>
<p>Dive into our newest collection of eco-friendly products! Let's make a difference together.</p>
<p>Discover the beauty of handcrafted artisanal items in our latest collection. Every piece tells a story.</p>

```

### Ad Banner displays on all pages

To display the ad banner appearing on all pages on the header, drag and drop the HTML widget to the corresponding position, paste the given code below to the HTML editor, then click Save HTML button.

```html
<p style="display:flex; align-items: center">
  <span>STAY AHEAD OF THE STYLE CURVE WITH OUR LATEST ARRIVALS -<a href="/shipping-returns/" style="font-weight: 500"> Discover Now</a></span>
</p>
```


**Watch the instruction video:**

<iframe width="760" height="515" src="https://www.youtube.com/embed/X-0U2gh2S54?si=LuJfGRh2pjO7FSL0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; pictre-in-picture; web-share" allowfullscreen></iframe>

### Discount banner

![discount-banner](img/discount-banner.jpg)

Drag & drop **Responsive | PapaThemes** to the corresponding position. In **SCREEN SIZE 1** set **Min** = `320px`, set **Max** = `801px` and change **Display** = `Hide`. To hide banner in tablet and mobile.

Drag & drop **Flex Banners | PapaThemes Beautify** below **Responsive | PapaThemes** widget, remove all banner except banner 1. Set **Image width** = `1170px` and **Image height** = `100px`.

In **Border radius** set `0px`.

In **Content**, hide **Heading text**.

In **General**, choose edit **Padding**, **Desktop** set **Left** and **Right** = `0`, **Top** = `20`, **Bottom** = `20`.

**Watch the instruction video:**

### Main Carousel

![main-carousel-manager](img/main-carousel-manager.jpg)

Upload the carousel images in **Storefront** > **Home Page Carousel**.

Go back to **Page Builder**, in **Theme Styles** > **Home Page**, make sure **Carousel** > **Show carousel** is selected. You can change the carousel styles and colors here.

To adjust the image height in mobile view, simply modify the **Mobile Image Height** to your preferred dimension.

**Watch the instruction video:**

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/796542010?h=3030ce28cf&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;" title="instr-home carousel"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

### Policy Delivery and Hotline Banner

![policy-delivery-hotline](img/policy-delivery.jpg)

In **Page Builder**, drag & drop **Layout** widget to the corresponding position. In **Layout background**, select `Color` in **Background** and set **Background color** = `#252424`

Change **Column** = `1`, set **Padding** = `0 0 0 0`.

Drag & drop **Callout Icons | PapaThemes Beautify** widget. Delete all other callouts except the first one.

For the **Width**, select the unit `%` and specify the values for different devices as follows: **Desktop** = `25%`, **Tablet** and **Mobile** = `40%`.

In the **Padding** section, set the values for different devices as follows: **Desktop** = `30 30 30 30`, **Tablet** and  **Mobile** = `20 20 20 20`.

![policy-delivery-hotline](img/policy-delivery-2.jpg)

Select your desired icon in the **Icon** section.

If your desired icon is not available in the widget, select **Custom** in **Icon** and paste code svg in text box, click **Save HTML**. Paste the link into the designated Link box.

Select `Custom` for the **Text style**. In **Font weight** select `Bold`. Customize the text content and choose your preferred Text color.

Enable **Show text**, to display fist text right below the icon. Select `Custom` for the **Text style ** . Set the **Font size** = `16px` for desktop devices. Adjust the **Font size(Mobile)** = `10px`. Customize the text content and choose your preferred Text color

![policy-delivery-first-text](img/policy-delivery-first-text.jpg)

Enable **Show second text**, to display second text. Select `Custom` for the **Second text style**. Set the **Font size** = `14px` for desktop devices. Adjust the **Font size(Mobile)** = `10px`. Customize the text content and choose your preferred Text color.

To make the text color lighter, click on **Text color** then click `+` icon, choose your desired color and in section `A`, adjust to 0.6 to make the text lighter.

![policy-delivery-second-text](img/policy-delivery-second-text.jpg)

Duplicate callout 1, 3 times to create 3 similar icons. Change the image and link of the icons just created.

### Product By Category

![Product by category](img/Product-by-category.jpg)

Navigate to **Theme Styles** > **Home Page** choose one of the sections and type `pbcst` to enable this block.

This section allow users to select categories, specify the number of products to be shown, and determine the number of sub-categories to display.

in **Theme styles** > **Home Page** find **Products by Category with Sorting Tabs**:

- Check the box labeled **Only load when scrolling to the viewport** to enhance site performance. The products in this block will load only when the user scrolls to this section.
- To specify the categories that should be displayed on the **Home Page**, enter the desired category IDs in the field below **Categories ID (separated by ,)**. Each ID should be separated by a comma. For example: 123,456,567.
- In the **Number of Categories** dropdown, select the desired number of categories to be displayed on the **Home Page**.
- **Default sorting** allows you to control the display of products within categories. You can choose from four options: `Newest`, `Featured`, `Best-selling`, and `Top-review`.
- Users can also adjust the number of products displayed on the Home Page by entering a number in the **Number of products** field
- Users can also specify the number of sub-categories to be displayed on the Home Page by entering a number in the **Number of subcategories** field.

![Product by category](img/Product-by-category-2.jpg)


### Featured Brands

![Featured-brand](img/featured-brand.jpg)

**Featured brand** will automatic load all brands of your store.

To enable **Featured brand**, in **Theme Styles** > **Homepage** > **Section** choose one of sections and type `featured_brands` to enable this block.

To change color background of this section click on **Background** and select color fit to design.

This section allow user change section tiltle and display/hide brands logo, in **Hompage** find **Featured brand** type your text in **Heading** and checked the **Show brand logo** to display brands logo.

### Top Categories

![Top-categories](img/Top-categories.jpg)

**Top Categories** will automatic load first level categories of your store.

To enable **Top Categories**, in **Theme Styles** > **Homepage** > **Section** choose one of sections and type `top_categories` to enable this block.

To edit color background of sections **Top Categories**, select your color in **Background** and type empty input `Background Image` in **Top Categories**.

![Top-categories](img/top-category-edit-color.jpg)

To edit background image of sections **Top Categories**. Dinosaur theme provides users with three options to change the background by modifying the **Background Image** field as shown below:

- `blank`: leave the field empty, the background will be specified follow **Background** field.

- `top-categories-men.png`: **Top Categories** will use the default image of the theme to set as background header.

![Top-categories](img/top-category-edit-bgimg.jpg)

- `link`: **Top Categories** will be the link you provided in the input to set the background.

![Top-categories](img/top-category-edit-bgimg-2.jpg)

This section allow user change section tiltle, in **Hompage** find **Top Categories** type your text in **Heading**.

### Special Products Tabs

![special-products-tabs](img/special-products-tabs.jpg)

You can configure special products tabs section settings in **Page Builder** > **Theme Styles** > **Home Page**, make sure one of the **Sections** field type `spt`.

In **New / Featured / Bestselling Tabs** section, Change **Number of products** = `5` and **Number of products load more on viewport** = `0`. You can change **Default tab** to `Featured`, `Bestselling` or `New`. **Display type** can be changed to `Carousel` or `Grid`. **Show more button**, **featured products**, **bestselling products**, **new products**, **categories** can be enabled by checked box.

### Featured Products

![featured-products](img/Feature-products.jpg)

You can set featured products in **Products**, click the **star** icon on the same row to set the product as featured.

Go back to **Page Builder** > **Theme Styles** > **Home Page**, make sure one of the **Sections** has typed `featured_products`. In **Featured products** section, you can change the **Heading**, **Number of products** to display, Number of product per row (**Columns**), changing **Display type** to `Carousel` or `Grid`, changing the **background color**, editing the link of **View all products**.

![featured-products](img/Feature-products-2.jpg)

To edit color background of this section, select your color in **Background** and type empty input `Featured products background image link` in **Featured products**.

To change background image of this section. Enter link image into the **Featured products background image link** input fit to design.

### New Products

![new-products](img/New-products.jpg)

You can configure new products section settings in **Page Builder** > **Theme Styles** > **Home Page**, make sure one of the **Sections** has typed `new_products` . In **New products** section, you can change the **Heading**, **Number of products** to display, Number of product per row (**Columns**), changing **Display type** to `Carousel` or `Grid`, changing the **background color**, editing the link of **View all products**.

![new-products](img/New-products-2.jpg)

To edit color background of this section, select your color in **Background** and type empty input `New products background image link` in **New products**.

To change background image of this section. Enter link image into the **New products background image link** input fit to design.

### Bestselling Products

![bestselling-products](img/Popular-product.jpg)

Bestselling products only display when your store has some order.

You can configure bestselling products section settings in **Page Builder** > **Theme Styles** > **Home Page**, make sure one of the **Sections** has typed `popular_products`. In **Best-sellers products** section, you can change the **Heading**, **Number of products** to display, Number of product per row (**Columns**), changing **Display type** to `Carousel` or `Grid`, changing the **background color**, editing the link of **View all products**.

![bestselling-products](img/Popular-product-2.jpg)

To edit color background of this section, select your color in **Background** and type empty input `Best-sellers products background image link` in **Best-sellers products**.

To change background image of this section. Enter link image into the **Best-sellers products background image link** input fit to design.

### Grid layout banners

![grid-man-banners](img/three-men-banner.jpg)

To create **grid layout banners** :

In **Page Builder**, drag & drop **Layout** widget to the corresponding position. Change **Column** = `1`, set **Padding** = `0 0 0 0`.

Drag & drop **Flex Banners | PapaThemes Beautify** widget into the **Layout**. Remove all banner except banner 1.

To edit **Banner 1**, change your image, set **Image width** = `1024px`, **Image height** = `500px`. Click **Show different image on mobile**, change your image in mobile, set **Image width** = `550px`, **Image height** = `500px`. Set **Border radius** = `0px`.

In **CONTENT**, hide `Heading text`.

In **GENERAL**. Set **Width (Desktop)** and **Width (Tablet)** = `40%`, **Width (Mobile)** = `100%`. Set **Padding (Desktop)** = `0 15 15 0`, **Padding (Tablet)** = `0 10 10 0`, **Padding (Mobile)** = `0 0 0 0`.

Duplicate banner 1 to 2 banners.

In **Banner 2**, change your image, set **Image width** = `1536px`, **Image height** = `500px`. Click **Show different image on mobile**, change your image in mobile, set **Image width** = `550px`, **Image height** = `450px`. Set **Border radius** = `0px`.

In **GENERAL**. Set **Width (Desktop)** and **Width (Tablet)** = `60%`, **Width (Mobile)** = `100%`. Set **Padding (Desktop)** = `0 0 15 15`, **Padding (Tablet)** = `0 0 10 10`, **Padding (Mobile)** = `0 0 0 0`.

In **Banner 3**, change your image, set **Image width** = `2560px`, **Image height** = `450px`. Click **Show different image on mobile**, change your image in mobile, set **Image width** = `550px`, **Image height** = `400px`. Set **Border radius** = `0px`.

In **GENERAL**. Set **Width (Desktop)**, **Width (Tablet)** , **Width (Mobile)** = `100%`. Set **Padding (Desktop)** = `15 0 0 0`, **Padding (Tablet)** = `10 0 0 0`, **Padding (Mobile)** = `0 0 0 0`.


### Recently Viewed Products

![bestselling-products](img/Recently-viewed-products.jpg)

Recently Viewed Products will be display automatically viewed any product.

You can configure recently viewed products section settings in **Page Builder** > **Theme Styles** > **Home Page**, make sure one of the **Sections** has typed `recentviewed`. In **Recently Viewed Products** section, you can change the **Heading**, **Number of products** to display, Number of product per row (**Columns**), changing **Display type** to `Carousel` or `Grid`, changing the **background color**, editing the link of **View all products**.

### Customer Service

![customer-service](img/customer-service.jpg)

To enable **Customer service**, in **Theme Styles** > **Homepage** > **Section** choose one of sections and type `customer_service` to enable this block.

To change color background of this section click on Background and select color fit to design.

This section allow user change section tiltle, in **Hompage** find **Customer service** type your text in Heading.

- **Phone number**: will automatically collect number from store profile.
- **Whapsapp**: To change Whatsapp number, go to **Footer** find **+Whatsapp** and type your number in the input field.
- **Email**: To change email number, go to **Footer** find **+Email** and type your email address in the input field.

![whatsapp-email](img/whatsapp-email.jpg)

To change Background of button, go to **General** find **General colors** change **Secondary color** to your color.

To change **Text**, **Icon**, color go to **General** find **Links colors** change **Default** to your color.

### About us

You can add About us block on Home Page. Drag & drop **Leaderboard Banner | PapaThemes Beautify** widget to the corresponding position.

On **BANNER** at `Content align`, click vertical top. Set `Banner height` and `Banner height (mobile)` = `364px`. Set `Background color` = `#FFFFFF`. Set your image on `Image`. In `Image fit` select `Fit to box`.

![about-us](img/aboutus-banner.jpg)

On **HEADING**. In `Heading style` select `Custom`. In `Font weight` select `Bold`. Set `Font size` = `32px`. Set `Heading color`, `Heading color (mobile)` = `#C72E2E`.

![about-us](img/aboutus-heading.jpg)

On **TEXT**. In `Heading style` select `Custom`. In `Font weight` select `Medium`. Set `Font size` = `18px`.

![about-us](img/aboutus-text.jpg)

On **ADVANCED**. In `Style for theme` select `Kitchenary`.

![about-us](img/aboutus-advanced.jpg)


### Recent Blog Posts

![edit-recent-blog](img/edit-recent-blog.jpg)

You can add blog posts in Storefront > Blog. Click the **+** button to add a new blog post. Make sure **Blog Visibility** is `on`.

To display the **recent blog** posts on the home page, go to **Page Builder**. In **Theme Styles** > **Home Page**, make sure one of Sections has typed `blog_recent`. Scroll down the Recent Blog section, you can configure **Heading**, **Number of posts** to display.

### Customer Reviews

![customer-reviews](img/customer-reviews.jpg)

Drag & drop **Layout** widget to the corresponding position.select Image in the Background section to upload your image, change image fit to fill. Change **Column** = `1`. Select **Column 1**, set **Padding** = `0 0 0 0`.

Drag & drop **Section Heading | PapaThemes Beautify** widget into the **Layout**. Typing your text (example "Customer Reviews"), select `custom` in **Text style** field, set **Font size** = `32px`, **Font size (Mobile)** = `20px`, **Text color** = `#FFFFFF`, **Padding** = `52 0 40 0`, **Padding (Mobile)** = `30 0 6 0`.

Drag & drop **Customer Reviews | PapaThemes Beautify** widget below **Section Heading | PapaThemes Beautify** widget. Make sure to remove all reviews except for the first one.

For each review, provide the following details:

**Title**: Enter the title of the review.

**Content**: Write the content of the review.

**Rating**: Choose the desired number of review stars.

**Author**: Specify the name of the reviewer.

To maintain consistency in the theme, select `Beautify Furniture` in the **Style for theme** option.

If you want to add more reviews, duplicate the first review as many times as needed and update the content for each review.


### Newsletter

![edit-newsletter](img/edit-newsletter.jpg)

To enable newsletter form, go to **Marketing** > **Email Marketing**, make sure **Allow Newsletter Subscriptions** is checked. Optionally select **Show Newsletter Summary** and enter the summary text as you want.

Go to Page Builder, in **Theme Styles** > **Footer** > **Newsletter** section.

Make sure **Show newsletter form** is selected. You can change the **Heading**, **background color**, **background image**, **button** and **text colors**.

**Watch the instruction video:**

<iframe width="760" height="515" src="https://www.youtube.com/embed/5HxXt7uaX5c?si=QjmxVqePqgfLxxm6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Newsletter Popup

![newsletter-popup](img/newletter-popup.jpg)

**Newsletter Popup**use the same content and heading with **Newsletter** in footer. Please find instruction to change content in **Newsletter**.

To change delay time and show up again peropd for display **Newsletter Popup**, in **Theme styles** > **General** > **Newsletter Popup** change **Show after page loaded (sec)** for delay time to display the popup, change **Don't show up again (sec)** for the popup re-appear again.

To change image in **Newsletter popup**, simply copy and paste your Image URL to **Newsletter Popup background URL**

![edit-newsletter-popup](img/newletter-popup-edit.jpg)


### Footer

![footer](img/footer.jpg)

In **Page Builder** > **Theme Styles** > **Footer**, you can configure the newsletter form appearance in **Newsletter** section, configure the footer link colors in **Main Footer** section, displaying store logo, contact info, store address,... **Show pages** allows to limit number of web page links to display. **Show categories** allows to limit number of category links to display. Similarly for **Show brands** option.

**Payment Icons** allows to select which payment icons to display.

**Copyright** allows to configure the copyright text.

**Watch the instruction video:**

<iframe width="760" height="515" src="https://www.youtube.com/embed/A481Na0Ec0Y?si=l12B8xW6ZszZjqp7" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


### Instagram photos

To display your Instagram photos, open <https://instagram.papathemes.com/> Follow the instruction on this page to [Connect your Facebook Page with your Instagram account](https://www.facebook.com/business/help/898752960195806). Then click **Login With Facebook** button and follow the further steps to authorize access permission. Click **Show Embedding Code** button to generate the code embedding to your web store. Choose **Preset** = `Carousel` and select **LazyLoad**.

Copy all the code appear in Step 1 & Step 2. For example:

```html
<script>!function(){var a=document.createElement("script");a.defer=!0,a.src="https://papathemes.s3.amazonaws.com/instagramapp/assets/js/embed-1.0.1.js",a.onload=function(){PapathemesInstagramApp.init({account_id:"****************",element_id:"papainstagram-render",limit:"20",preset:"grid",lazyload:"false"})},document.body.appendChild(a)}();</script>

<div id="papainstagram-render"></div>
```

Go back to your store Page Builder. Drag & drop the HTML widget to the corresponding position. Paste the generated code above to the HTML editor, and click **Save HTML** button. Your Instagram photos should display like our demo store.

Please note that the app only updates your latest uploaded photos every 6 hours.

To create the title, drag & drop the **Section Heading** widget to above the Instagram photos. Set **Padding** = `40 0 40 0` and **Padding (Mobile)** = `20 0 20 0`.

**Watch the instruction video:**

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/795504772?h=06cb1784a7&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;" title="instr-instagram"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

### Display Custom Footer Links

In **Page builder** > **Custom Widget** find **Footer links | PapaThemes Beautify** widget then drag and drop the widget to corresponding position in **Footer**.

Select the **Column 1** and change **padding** to `0 0 0 0`.

In **design** you can type your link content and click on the **insert/edit link** button as picture below:

![footer-links](img/footer-link-widget.jpg)

In the popup window, copy your web link to `URL`. On the **Open links..** field you can select how your link could be open in **New Window** or **Current Window**
 
 ![Insert-links](img/insert-links.jpg)

### Unique Sport-Inspired Fashion

![Product Tag Widget](img/product-tag-widget.jpg)

Drag & drop **Layout widget** to the corresponding position, change **Column** = `1`, set **Padding** = `0 0 0 0`.

Drag & drop **Section Heading | PapaThemes Beautify** widget into the **Layout**. Typing your text (example "Unique Sport-Inspired Fashion"), select `custom` in **Text style** field, set **Font size** = `32px`, **Font size(Mobile)** = ` 20px`, **Font weight** = `Bold`, **Text color** = `#000000`, **Padding** = `10 0 40 0` and **Padding (Mobile)** = `18 0 18 0`.

Drag & drop **Product Tags PapaThemes Dinosaur** widget below **Section Heading | PapaThemes Beautify** widget.

In **Settings** > **General**:

Upload your **Image**, Set **width** and **Height** follow Image size.

Checked **Display in a container DIV** and **Lazyload image**.

Select `Fit to box` for the **Image fit**.

![Product Tag Widget](img/product-tag-widget-settings-general.jpg)

In **Product 1**:

Enter **Product SKU** (Hover over the tag icon to check whether SKU added to the tag).

Select `Tag` for the **Tag Icon**, set **Tag Icon Color** = `#67DAC5`.

Click the **Set Tag Position** button to activate the function that allows you to change the tag's position. Select the tag and then choose the position where you want to move it. Alternatively, you can also set the position manually by entering the position value in **Position - X** and **Position - Y**.

Click on the plus button next to **PRODUCT TAGS PAPATHEMES DINOSAUR** to create more products and set up the same as **Product 1**.

![Product Tag Widget](img/product-tag-widget-settings.jpg)

## Setting Up Woman Style Home Page

### General

You can read these common instructions in **Setting Up Man Style Home Page** chapter:

- [Header](#header)
- [Top Banner](#top-banner)
- [Ad Banner displays on all pages](#ad-banner-displays-on-all-pages)
- [Discount banner](#discount-banner)
- [Main carousel](#main-carousel)
- [Policy Delivery and Hotline Banner](#policy-delivery-and-hotline-banner)
- [Product By Category](#product-by-category)
- [Featured Brands](#featured-brands)
- [Top Categories](#top-categories)
- [Special Products Tabs](#special-products-tabs)
- [Featured Products](#featured-products)
- [New Products](#new-products)
- [Bestselling Products](#bestselling-products)
- [Recently viewed products](#recently-viewed-products)
- [Customer service](#customer-service)
- [About us](#about-us)
- [Recent blog posts](#recent-blog-posts)
- [Customer reviews](#customer-reviews)
- [Newsletter](#newsletter)
- [Newsletter Popup](#newsletter-popup)
- [Footer](#footer)
- [Instagram photos](#instagram-photos)
- [Display custom footer links](#display-custom-footer-links)
- [Unique Sport-Inspired Fashion](#unique-sport-inspired-fashion)

### Grid layout banners

![grid-woman-banners](img/three-woman-banner.jpg)

To create **grid layout banners**:

In **Page Builder**, drag & drop **Layout** widget to the corresponding position. Change **Column** = `1`, set **Padding** = `0 0 0 0`.

To edit **Banner 1**, change your image, set **Image width** = `564px`, **Image height** = `395px`. Click **Show different image on mobile**, change your image in mobile, set **Image width** = `550px`, **Image height** = `500px`. Set **Border radius** = `0px`.

In **CONTENT**, hide `Heading text`.

In **GENERAL**. Set **Width (Desktop)** and **Width (Tablet)** = `32%`, **Width (Mobile)** = `100%`. Set **Padding (Desktop)** = `0 15 15 0`, **Padding (Tablet)** = `0 10 10 0`, **Padding (Mobile)** = `0 0 0 0`.

Duplicate banner 1 to 2 banners.

In **Banner 2**, change your image, set **Image width** = `1126px`, **Image height** = `395px`. Click **Show different image on mobile**, change your image in mobile, set **Image width** = `550px`, **Image height** = `500px`. Set **Border radius** = `0px`.

In **GENERAL**. Set **Width (Desktop)** and **Width (Tablet)** = `64,5%`, **Width (Mobile)** = `100%`. Set **Padding (Desktop)** = `0 0 15 15`, **Padding (Tablet)** = `0 0 10 10`, **Padding (Mobile)** = `0 0 0 0`.

In **Banner 3**, change your image, set **Image width** = `1720px`, **Image height** = `349px`. Click **Show different image on mobile**, change your image in mobile, set **Image width** = `550px`, **Image height** = `500px`. Set **Border radius** = `0px`.

In **GENERAL**. Set **Width (Desktop)**, **Width (Tablet)** , **Width (Mobile)** = `100%`. Set **Padding (Desktop)** = `15 0 0 0`, **Padding (Tablet)** = `10 0 0 0`, **Padding (Mobile)** = `0 0 0 0`.

### Homepage Banner Under Product by Category

![grid-woman-banners](img/woman-banner.jpg)

In **Page Builder**, drag & drop **Layout** widget to the corresponding position. Change **Column** = `1`, set **Padding** = `0 0 0 0`.

Drag & drop **Flex Banners | PapaThemes Beautify** widget into the **Layout**. Remove all banner except banner 1.

To edit **Banner 1**, change your image, set **Image width** = `1400px`, **Image height** = `350px`. Click **Show different image on mobile**, change your image in mobile, set **Image width** = `550px`, **Image height** = `290px`. Set **Border radius** = `0px`.

In **CONTENT**, hide `Heading text`.

In **GENERAL**. Set **Width (Desktop)** and **Width (Tablet)** = `32%`, **Width (Mobile)** = `100%`. Set **Padding (Desktop)**, **Padding (Tablet)** and **Padding (Mobile)** = `0 0 0 0`.

## Setting Up Kid Style Home Page

### General 

You can read these common instructions in **Setting Up Man Style Home Page** and **Setting Up Woman Style Home Page** chapter:

- [Header](#header)
- [Top Banner](#top-banner)
- [Ad Banner displays on all pages](#ad-banner-displays-on-all-pages)
- [Discount banner](#discount-banner)
- [Main carousel](#main-carousel)
- [Policy Delivery and Hotline Banner](#policy-delivery-and-hotline-banner)
- [Product By Category](#product-by-category)
- [Featured Brands](#featured-brands)
- [Top Categories](#top-categories)
- [Special Products Tabs](#special-products-tabs)
- [Featured Products](#featured-products)
- [New Products](#new-products)
- [Bestselling Products](#bestselling-products)
- [Grid layout banners](#grid-layout-banners)
- [Recently viewed products](#recently-viewed-products)
- [Customer service](#customer-service)
- [About us](#about-us)
- [Recent blog posts](#recent-blog-posts)
- [Customer reviews](#customer-reviews)
- [Newsletter](#newsletter)
- [Newsletter Popup](#newsletter-popup)
- [Footer](#footer)
- [Instagram photos](#instagram-photos)
- [Display custom footer links](#display-custom-footer-links)
- [Unique Sport-Inspired Fashion](#unique-sport-inspired-fashion)

### Homepage left sidebar layout

![Left Sidebar](img/left-sidebar-img.jpg)

To display the left sidebar on the home page, go to **Page Builder**. In **Theme Styles** > **Home Page** > **Left Sidebar**, ensure that at least one of the three options is filled in. You can also change the order of each section by section name as below:

- `popular_producs`: to display best seller products
- `new_products`: to display new arrival products
- `featured_products`: to display feature producs.

![Left Sidebar](img/left-sidebar-settings.jpg)

Note: Leftside bar can only display three section above. To modify the header or configure each section, kindly scroll down to the specific section configuration you wish to alter.

### Homepage Left Sidebar Banner

![Left Sidebar Banner](img/left-sidebar-banner.jpg)

To display the left sidebar banner on the home page, go to **Page Builder**.

Drag & drop **Layout widget** to the corresponding position, change **Column** = `1`, set **Padding** = `0 0 0 0`.

Drag & drop **Flex Banners | PapaThemes Beautify** widget into the **Layout**. Delete all other **Banner** except the first one.

To edit **Banner 1**, change your image, set **Image width** = `800px`, **Image height** = `1000px`. **Image alt text** refers to modifying the caption of an image according to your preferences. **Border radius** = `8px`.

In **Content** set invisible for all **Heading text**, **Description text**, **Action button**

In the **Padding** section, set the values for different devices as follows: **Desktop**, **Tablet** and **Mobile** = `0 0 0 0`.

### Homepage Customer Reviews Left Sidebar

![Customer's Reviews](img/kid-customer-reviews.jpg)

To display the **Customer's Reviews** on the home page.

Drag & drop **Layout widget** to the corresponding position, change **Column** = `1`, set **Padding** = `0 0 0 0`.

Drag & drop **Section Heading | PapaThemes Beautify** widget into the **Layout**. Typing your text (example "Customer's Reviews").

- **Text style** = `Custom`
- **Font size** = `24px`
- **Font size (Mobile)** = `20px`
- **Margin** = `0 0 30 0`
- **Padding** and **Padding (Mobile)** = `0 0 0 0`

![Customer's Reviews Heading Setting](img/customer-reviews-head-settings.jpg)


Drag & drop **Customer Reviews | PapaThemes Beautify** widget below **Section Heading | PapaThemes Beautify** widget. Delete all other **Review** except the first one.

To edit **Review 1**:

- In **Avatar** > set **Type** = `Hide`.
- Enter your **Title** (example "They Look Even Better Than")
- Enter your **Content** (example "They look even better than the picture. I got these jeans for my son. Not too tight. He's a husky teen and they look and fit perfectly. He's 5'7 and they're not too short on him.")
- Select **Rating** = `Hide`.
- Enter your **Author** (example "<strong>Chanel W.</strong> <strong>January 25, 2023</strong>")
- Select **Style for theme** = `Beautify Furniture`.
- Checked **Display reviews in container div**.

Duplicate review 1 if you have more than 1 review want to display and change the content.

![Customer's Reviews Heading Setting](img/customer-reviews-settings.jpg)

### Homepage About Us Left Sidebar

Desktop :

![About Us Desktop](img/about-us-dt.jpg)

To display the **About Us** on the home page.

Drag & drop **Layout widget** to the corresponding position, change **Column** = `1`, set **Padding** = `0 0 0 0`.

Drag & drop **Section Heading | PapaThemes Beautify** widget into the **Layout**. Typing your text (example "About Us").

- **Text style** = `Custom`
- **Font weight** = `Normal`
- **Font size** = `24px`
- **Font size (Mobile)** = `20px`
- **Margin** = `0 0 30 0`
- **Padding** and **Padding (Mobile)** = `0 0 0 0`

Drag & drop **Flex Banners | PapaThemes Beautify** widget below **Section Heading | PapaThemes Beautify** widget. Delete all other **Banner** except the first one.

To edit **Banner 1**, change your image, set **Image width** = `800px`, **Image height** = `500px`. **Image alt text** refers to modifying the caption of an image according to your preferences. **Border radius** = `8px`.

In **Content** set invisible for all **Heading text**, **Description text**, **Action button**

For the **Width**, select the unit `auto`

In the **Padding** section, set the values for different devices as follows: **Desktop**, **Tablet** and **Mobile** = `0 0 0 0`.

In **Settings** > **General** :

Choose **Padding**: set the values for different devices as follows: **Desktop**, **Tablet** and **Mobile** = `0 0 15 0`.

Drag & drop **Text** widget below **Flex Banners | PapaThemes Beautify** widget. Enter your text (example "Unlock Your Style Potential, Embrace Confidence: Discover the Epitome of Men's Fashion Excellence at Our Website!")

- **Text style** = `Custom`
- **Font weight** = `Semi Bold`
- **Font size** = `16px`
- **Text color** = `#33352F`
- **Margin** = `0 0 15 0`
- **Padding** = `0 0 0 0`

Drag & drop **Text** widget below **Text** widget. Enter your text (example "Welcome to our men's fashion website - the ideal destination to enhance your style. With a deep passion for men's fashion, we are confident in providing you with a fantastic shopping experience and the widest selection")

- **Text style** = `Custom`
- **Font weight** = `Normal`
- **Font size** = `16px`
- **Text color** = `#646464`
- **Margin** = `0 0 20 0`
- **Padding** = `0 0 0 0`

Drag & drop **HTML** widget below **Text** widget. Enter your content (example `<a href="#" class="readMore-button" style="">Read More<svg class="icon"><use xlink:href="#icon-circle-arrow-right"></use></svg></a>`).

## Customizing Products Display

### Product Card

![configure-product-card](img/configure-product-card.jpg)

Configuring product cards in **Page Builder** > **Theme Styles** > **Products** > **Product cards**.

- **Alignment**: Specifying content alignment `left` or `center`.
- **Product title color**: Specifying the product name's color.
- + **Hover**: Specifying color when hover or focus.
- **Product countdown color**: specify number's color in countdown box.
- - **Background**: Specify background's color of countdown box.
- **Show second image on hover**: Displaying the second image when hover the product card.
- **Show SKU**: toggle displaying the product SKU.
- **Show Brand**: toggle displaying Brand of product.
- **Show Add to Cart button**: toggle on to make Add to Cart button always visible.
- **Show quantity input**: toggle on to display quantity input. If toggle of input field will not visible client cannot adjust the quantity in card.
- + **Border**: Specifying the button border color.
- **Show swatch/rectangle options**: Allows to display with swatch/rectangle type product option on every product card. It's helpful to display different product variants like colors or sizes.
- **Show only option name**: enter the option name to display in card.
- **Swatch sizes**: Specifying the swatch color/image size.
- **Show countdown Flash Sale**: Display countdown timer for Flash Sale products.
- **Show corresponding variant image when filtered**: toggle this option will help display variant image instead of thumbnail image when using Faceted filter. (Example: filter color Ogrance card will display image of variant Ogrance).
- **Show call us for price**: to display call us for price message.
- **Show custom fields**: enter the custom field name and seperate each custom field with `|` to display them in card.
- **Badge position**: also to configure the sale badge position to `Top Left` or `Below image`.

### Displaying product price ranges

By default product price ranges is enabled. To turn off, Go to **Page Builder** > **Theme Styles** > **Products** > uncheck **Price ranges** checkbox.

**Show retail price**: Toggle displaying the product retail prices.


### Hiding prices for non logged in customers

To turn on this feature, go to **Page Builder** > **Theme Styles** > **Products** > tick **Restrict Purchase to Login** checkbox.

![hide-prices](img/hide-prices.jpg)

### Redirecting to cart page after product added to cart

By default the cart popup is displayed, if you want to take customer to the cart page instead, go to **Page Builder** > **Theme Styles** > **Products** > tick **Redirect to cart page after add to cart** checkbox.

### Showing/Hiding Quick-View button

By default quick-view buttons appear on all product cards. To hide it, go to **Page Builder** > **Theme Styles** > **Products** > un-tick **Show Quickview** checkbox.

### Showing/Hiding the quantity box on PDP

By default the quantity box shows up, to hide it, go to **Page Builder** > **Theme Styles** > **Products** > un-tick **Show quantity selection on product pages** checkbox.

### Customizing the popup displayed after product added to cart

In **Page Builder** > **Theme Styles** > **Products** > **Popup after added to cart**:

- `Cart Preview`: Displaying the whole shopping cart popup on the right side.
- `Hide`: Not show any popup.

Mini added to cart popup:

![cart-preview](img/cart-preview.jpg)

### Displaying Recently Viewed Products

Recently viewed products only display for logged-in customers.

To enable it, go to **Page Builder** > **Theme Styles** > **Products** > **Show recently viewed** select number of products to display.


### Customizing Price Labels

You can customize sale price label, before sale price label, retail price label or regular price label in 
**Page Builder** > **Theme Styles** > **Products** > **Price Labels**

![configure-price-labels](img/configure-price-labels.jpg)

### Displaying product weight, dimensions on PDP

Go to **Page Builder** > **Theme Styles** > **Products** > **Product Page**.

- Tick **Show product weight** checkbox.
- Tick **Show product dimensions** checkbox.

### Display sale badge on PDP

Go to **Page Builder** > **Theme Styles** > **Products** > **Product Page**.

- Tick **Show sale badge** checkbox.

### Sale badge, Condition badge and custom text badges

![product-badges](img/product-badges.jpg)

Displaying the sale badge in **Page Builder** > **Theme Styles** > **Products** > **Product sale badges**, tick **Show sale badges**.

- **Label**: Specifying the badge text.
- **Text color**: Specifying the badge text color.
- **Background color**: Specifying the badge background color

Displaying the condition badge in **Condition badges**, tick **Show condition badges**.

Displaying the condition badge in **Custom badges**, tick **Enable custom badge from '__badge' custom field**. Edit product, add custom field with name `__badge` and value is the badge text.

- **Text color**: Specifying the text color of the custom badge.
- **Background color**: Specifying the background color of the custom badge.

### Displaying Image gallery 

#### Displaying thumbnail as a slider

In **Page Builder** > **Theme Styles** > **Products** > **Product Page**, **Enable thumbnail carousel** section, you can change display thumbnail images to slider or grid.

- `1 row`: Sub-images are displayed in the slider on 1 row.

- `2 rows`: Sub-images are displayed in the slider on 2 row.

- `Hide`: All sub-images are displayed as grid.

![thumbnail-2](img/thumbnail-2.jpg)


#### Displaying product image thumbnails vertically

In **Page Builder** > **Theme Styles** > **Products** > **Product Page**, checked **Show image thumbnails vertically** to display product thumbnails vertically, otherwise it's displayed horizontally.

Checked **Show image thumbnails vertically**:

![thumbnails-vertically](img/thumbnail-vertical.jpg)

To specify the number thumbnail display in slider simply enter your desire number in **Number of visible thumbnails**.

### Video image product detail page

In **Page Builder** > **Theme Styles** > **Products** > **Product Page** find **Show videos** select `tab` or `image gallery` to change display video position.

Videos displayed in **tab** options:

![video image product detail tab option](img/video-image-PDP-tab.jpg)

Videos displayed in **image gallery** option:

![video image product detail image gallery option](img/video-image-PDP-image-gallery.jpg)

### Setup bulk pricing 

Bulk pricing discounts can be managed under the Pricing section when adding or editing a product. Click Show **Advanced Pricing** to view bulk pricing fields, among other pricing product fields. Bulk pricing of Dino theme auto display under price slider. customer can slide to to increase product quantity to reach each bulk pricing point.

- **% Discount:** takes a percentage off the total product price when the quantity threshold is met ("Order 2 or more, get 10% off").

![bulk-pricing-discount](img/bulk-discount.jpg)

- **$ Fixed Amount:** specifies a fixed price for each unit when the quantity threshold is met ("Get 2 for $15 each"). This discount type is not available for category-level bulk discounts.

![bulk-pricing-discount](img/bulk-fixed.jpg)

- **$ Off/Unit:** subtracts a fixed amount from the price of each unit when the quantity threshold is met ("Save $7 on each when you buy 2 or more")

![bulk-pricing-off-unit](img/bulk-off-unit.jpg)

### Displaying sticky Add to Cart button on PDP on mobile

In **Page Builder** > **Theme Styles** > **Products** > **Product Page**, tick **
Show sticky Add to Cart on mobile**.

![Show sticky Add to Cart on mobile](img/sticky-add-to-cart.jpg)

### Displaying product custom fields in a separated tab

In **Page Builder** > **Theme Styles** > **Products** > **Product Page**:

- Tick **Show custom fields in tab** checkbox.
- Enter the tab title in the next **Tab title** box.

![product-custom-fields-tab](img/product-custom-fields-tab.jpg)

### Custom tabs

![Custom-tab-sample](img\custom-tab-sample.jpg)
To add the **custom tabs** in product pages, edit your product description, click on **HTML button** to open HTML Source Editor:

![Custom-tab](img\custom-tab.jpg)

Use the editor at the **[link](https://bc-supermarket-docs.papathemes.com/customization/product-page#custom-tabs)** to generate HTML for your **custom tabs**. Click Export HTML button, copy & paste the generated HTML at the end of HTML Source Editor.

### Displaying Delivery & Returns tab

In **Page Builder** > **Theme Styles** > **Products** > **Product Page**:

- Tick **Show Delivery & Returns tab** checkbox.
- Enter the tab title in the next **Tab title** box.

You can add specific content or global content using BC widgets:

![add-widgets-to-delivery-returns-tab](img/add-widgets-to-delivery-returns-tab.jpg)


### Numbers of products, reviews, thumbnails

In **Page Builder** > **Theme Styles** > **Products** > **Product Page**:

- **Number of Product Reviews**: Specifying number of product reviews displayed.
- **Number of Related Products**: Specifying number of related products displayed.
- **Number of Customers Also Viewed Products**: Specifying number of customer also viewed products displayed.

### Displaying Swatch Options in the dropdown select box

In **Page Builder** > **Theme Styles** > **Products** > **Swatch display type**:

- `Default` (Square): Displaying the regular swatches by default.
- `Dropdown`: Displaying swatches in the dropdown select box.
- `Dropdown + Square`: Displaying swatches in the dropdown select box in addition to regular swatches.

![swatch-dropdown](img/swatch-dropdown.jpg)


### Displaying Frequently Bought Together Products

![frequently-bought-together](img/frequently-bought-together.jpg)

Enabling this feature in **Page Builder** > **Theme Styles** > **Products** > **Frequently Bought Together**, Select **Position** to display it.

- **Load products from**: Specifing products to display here.
  - `Custom fields __alsobought`: Specifying the relevant products in product custom fields with name `__alsobought` and value is the relevant product ID. For example:
  ![edit-product-bought-together](img/edit-product-bought-together.jpg)
  - `Related products`: Pulling from the related products.
  - `Similar by biews`: Pulling from customer also viewed products.
- **Auto select all items**: Auto select or unselect all frequently bought together products.
- **Thumbnail size**: Specifying the thumbnail image size.
### Configuring swatch dimension

In **Page Builder** > **Theme Styles** > **Products** > **Swatch display type** > Set **Swatch size**.


### Configuring image sizes


In **Page Builder** > **Theme Styles** > **Products** > **Image Sizes**:

- Main product images: Specifying the main product image size displayed on PDP.
- Thumbnail image: Specifying the product thumbnail size.
- Zoomed image: Specifying the zoomed image size.
- Image in gallery view: Specifying product card image size.

### Shipping countdown

![shipping-countdown](img\shipping-countdown.jpg)

To enable shipping countdown, **Theme styles** > **Product page**  find **shipping countdown** field and input your cut off time. Find and copied your timezone from wikipedia `https://en.wikipedia.org/wiki/List_of_tz_database_time_zones` to **timezone** field.

To disable shipping countdown simply leave **shipping countdown** field empty.

Note: The time before cut off the message will show **shipping today** after cut off the message will show **shipping tomorrow**

### Coupon

![Coupon-ticket](img/coupon-ticket.jpg)

In **Page Builder**, drag and drop widget **Coupons | PapaThemes Dinosaur** to correct widget region as picture below.

Set **Layout** > **Column** `padding` = `0`.

![Coupon-ticket](img/coupon-region.jpg)

To edit **Coupon**. To modify the title and details of the coupon ticket, simply click on the title or content of ticket and adjust them. Copy Simply click on the title of the ticket and adjust them according to the **Marketing** > **Coupon codes**. Then copy Coupon code of **Coupon codes** to input `Coupon code` of **Coupon** widget.

![Coupon-ticket](img/set-coupon-code.jpg)

Coupons will appear in the sections below.

`Cart popup`:

![Coupon-ticket](img/coupon-cartpopup.jpg)

`Cart Page`:

![Coupon-ticket](img/coupon-cartpage.jpg)

### Flash sales

![Flash-sales](img\flash-sales.jpg)

![Flash-sales](img\flash-sales-card.jpg)

To create flash sales for each product and product card, in **product** section select the product that you want to add Flash Sales.

Find customer fields, click on add **Add Custom Field**. Enter `__countdown_label` into **Custom Field Name**. In **Custom Field Value**, type your content following format: `<your banner name>|<end in>` (example: FLASH SALES|ENDS IN). 

Create second custom field, enter `__countdown_date` into **Custom Field Name**. In **Custom Field Value**, input your cut off time following the format: `<yyyy>-<mm>-<dd> <hh>:<mm>:<ss><timezone>` (example: 2023-03-15 17:00:00-7).

Note:

- `<yyyy>-<mm>-<dd>` is optional. If the date is not entered, the banner will repeat automatically right after pass cut off time.
  
- `<hh>:<mm>:<ss>` is 24 hour format.
  
- `<timezone>` only input `+ or -` and `number` example: `+7`. if timezone are not entered, the countdown time will be different in different countries.

- Make sure you product also have sale price in orde for Flash Sale display. When you remove the **sale price** **Flash Sale** banner will auto disable.

### Brand logo in product detail

![brand logo in product detail](img/brand-logo.jpg)

To display **Brand logo** in product detail, in **Page Builder** > **Products** > **Product Page** find and check **Show brand image** option.


### Ask question

In **Page Builder** > **Theme Styles** > **Products** > **Product Page** find **Ask question (contact page URL)** and enter `/contact-us/` to display **Ask Questions?**.

![ask question](img/ask-question.jpg)


### Instruction & size guide

![Instruction & size guide](img/Instruction-size.jpg)

To create additional information link:

In **Storefront** > **Web Pages**, click on the **Create a Web Page** button to create new webpage.

In **Web Page Details**, enter your page name in **Page Name** field, **Page URL** will be automatically generated. In **Page content** field enter your content.

Uncheck **Navigation Menu** options.

In **Advanced Options** set **Sort Order** = `2`.

To display the additional information link in the product detail page:

In **Products**, select the product you want to display the link. Find **Custom Fields**, created new custom field. Set **Custom Fields Name** = `__guide_popup` and **Custom Fields Value** = `<your page name>|<Page URL>` (example: `Instruction|/instruction/`) then save.

### Below add to cart banner

To create **Below add to cart banner**, in **Page builder** drag and drop **Layout widget** to corresponding position.

Select **Column 1**, set **Padding** = `0 0 0 0`.

Drag and drop **Callout icon | PapaThemes Beautify widget** into column 1, delete all icons except callout icon 1.

In **Styles** select `Left`, set **Padding** for all desktop, mobile and table = `0`.

In **Icon** change to `Choose Image`, in **Icon image** select your desire image.

To input your text into the widget, simply type it into the text field located in the design window.

![Below add to cart banner](img/banner-below-add-to-cart.jpg)

## Customizing Category Pages

Configuring the category pages in **Page Builder** > **Theme Styles** > **Products** > **Category Page**.

### Category Layout

Theme supports displaying category Page layout in `Full width` mode or `Left sidebar` mode. In **Layout**, select the particular display mode for default display.

- **Layout** = `Full width`

![full-width](img/category-fullwidth.jpg)

- **Layout** = `Left sidebar`
 
![left-sidebar](img/category-leftsidebar.jpg)

### Products Display Type

Theme supports displaying products in **grid** mode (2, 3, 4 or 5 products per row), in **list mode** or **bulk order** mode. In **Products display type**, select the particular display mode for default display.

- **Display type** on the right allow your customers to change product category display by themselves.
![products-display-type-by-customer](img/products-display-type-by-customer.png)

**Grid:**

![products-display-type-grid](img/product-display-type-grid.jpg)

**List:**

![products-display-type-list](img/products-display-type-list.jpg)

**Bulk order:**

![products-display-type-bulk](img/products-display-type-bulk.jpg)

### Display Bulk Order layout

To display this bulk order layout, select **Products display type** = `Bulk order`.

![products-display-type-bulk-order](img/products-display-type-bulk-order.jpg)

### Displaying Shop by Brand

- **Shop by Brand**: Specifying number of popular brands to display.

![popular-brands-sidebar](img/popular-brands-bar.jpg)

### Displaying Price Slider

- **Shop by Price**:
  - `Slider`: Displaying the price slider.
  - `List`: Displaying price list.
  - `Hide`.

![shop-by-price-slider](img/shop-by-price-slider.jpg)

### Infinite Products Loading

This feature allows you to choose the method of loading more products in the current catalog.

![infinite-product-loading](img/infinite-product-loading.jpg)

**Infinite Products Loading**:

  - `On scroll`: Products will automatic loadout when scrolling down.

  - `Load more button`: Click on the **Load more button** to continue loading more products.

  - `Off`: Show **page numbers** and **arrow** button as original. Click on button to see more products.

### Display contextual search

This feature allows searching products within the current category and the current selected filter.

![contextual-search](img/contextual-search.jpg)

Select **Show quick search in category** = `Show` to enable it.

- **+ Show results in descendent categories**: if selected, it also displays results in the descendent categories.

### Common Settings

- **Number of products per page**: Specifying number of products to display per page.
- **Show category image**: Displaying the category image or not.
- **Show category description on AMP page**: Displaying category description on AMP category page or not. If the category content contains images, the AMP page could be invalid. It's recommended to turn off this option.

## Customizing Brand Page & Search Page

Configuring the brand page in **Page Builder** > **Theme Styles** > **Products** > **Brand Page**.

- **Number of brands per page**: Specifying number of brands to display per page.
- **Number of products per page**: Specifying number of products to display per page.
- **Brand image in gallery view**: Specifying the brand card image size.
- **Brand image in brand page**: Specifying the large image size displayed on the brand page.

Configuring the search results page in **Page Builder** > **Theme Styles** > **Products** > **Search results**.

- **Number of products per page**: Specifying number of products to display on the search results page.

### Displaying brand quick-view introduction

![brand-quick-view](img/brand-quick-view.jpg)

In **Marketing** > **Marketing Banner**, click **Create a Banner** button. 

- Enter the brand introduction content to **Banner Content**.
- Select **Show on Page** = `For a Specific Brand` and select the corresponding brand.
- Select **Location** = `Bottom of Page`.
- Then click **Save** button to finish.

Watch the instruction video:

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/796915050?h=fa4bc20f8c&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;" title="Instr-Brand description"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>

### Display product per page

To change number products display per page in **Product** section find **Search page** then change **Number of products per page**:

![Search-product-number](\img\product-search-page.jpg)

## Customizing Cart page

### Display free shipping message in cart page.

Not qualify message

![Not-qualify](\img\not-egilible.jpg)

Qualify message

![qualify](\img\promotion-qualify.jpg)

In **Marketing** > **Promotion** click on **create** and select **With legacy editor**

In **Promotion detail** name your promotion 

In **promotion type** select `Orders totaling more than X amount get free shipping to specific shipping zones` at the field **spend at least** type your amount

![free-shipping-editor](\img\free-shipping.jpg)

In **Promotion option** type your message at **Congratulations Banner Message** to display for cart have qualified and type your message for cart have not qualify at **Upsell Banner Message** with format `[your text] %%condition.remaining%% [your text]` then click save

![promotion-message](\img\Promotion-message.jpg)




