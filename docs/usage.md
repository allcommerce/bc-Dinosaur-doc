# Usage Guide

## Get Started

Thanks for using our theme!

To set up the theme exactly like our demo stores, you may need to install the our free app **[PapaThemes Widgets](https://www.bigcommerce.com/apps/papathemes-widgets/)**. This app provides additional widgets to build the content in Page Builder visually without coding skill.

For displaying your Instagram photos on your website, you can use our free tool **[PapaThemes Instagram](https://instagram.papathemes.com/)**. We will guide you step by step later in this manual.

### Customizing Typography, Fonts and Colors

Customizing Typography, Fonts and Colors, Buttons in **Page Builder** > **Theme Styles** > **General**. There are dozens of options to help you customize your website beautifully and uniquely.

#### Using Google Fonts

The Dinosaur theme supports Google Fonts integration for both general text and headings. Here's how to configure custom Google Fonts:

![edit-google-font](img/edit-google-font.jpg)

##### Setting Up General Text Font

1. Navigate to **Page Builder** > **Theme Styles** > **General**
2. In the **Font family** dropdown, select your preferred font or choose to use a custom Google Font
3. To use a custom Google Font, enter the font name in the text field below the dropdown using this format:
   ```
   Google_FontName_FontWeight
   ```

**Examples:**

- `Google_Quicksand_400` - for Quicksand font with regular weight (400)
- `Google_Roboto_300` - for Roboto font with light weight (300)
- `Google_Open+Sans_600` - for Open Sans font with semi-bold weight (600)

**Note:** Use `+` to replace spaces in font names (e.g., `Open+Sans` instead of `Open Sans`)

##### Setting Up Headings Font

1. In the same **General** section, scroll down to the **Headings** area
2. Use the **Font family** dropdown to select a different font for headings
3. For custom Google Fonts in headings, enter the font name using the same format:
   ```
   Google_FontName+FontVariant_FontWeight
   ```

**Examples:**

- `Google_Quicksand+Black_700` - for Quicksand Black variant with bold weight (700)
- `Google_Montserrat+Bold_700` - for Montserrat Bold variant
- `Google_Poppins+Medium_500` - for Poppins Medium variant

##### Font Weight Reference

Common font weights you can use:

- `100` - Thin
- `200` - Extra Light
- `300` - Light
- `400` - Regular (Normal)
- `500` - Medium
- `600` - Semi Bold
- `700` - Bold
- `800` - Extra Bold
- `900` - Black

##### Best Practices

1. **Font Availability**: Ensure the Google Font you're using is available in the weight you specify
2. **Performance**: Limit the number of different font weights to improve page loading speed
3. **Readability**: Choose fonts that are easy to read on all devices
4. **Consistency**: Use a maximum of 2-3 different fonts throughout your website

##### Troubleshooting

If your custom Google Font doesn't appear:
1. Check the font name spelling and format
2. Verify the font weight is available for that font family
3. Ensure you're using underscores (_) and plus signs (+) correctly
4. Clear your browser cache and refresh the page

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


## Importing Sample Products

To set up your store to work exactly like our demo stores, you can import sample products using the following steps:

**Available Sample Products:**

- **Hoodie Sweatshirt Loose Fit Fashion Pullover Hoodie Casual**
    - Product link: [https://dinosaur-man-demo.mybigcommerce.com/hoodie-sweatshirt-loose-fit-fashion-pullover-hoodie-casual/](https://dinosaur-man-demo.mybigcommerce.com/hoodie-sweatshirt-loose-fit-fashion-pullover-hoodie-casual/)
    - Download: [samples/hoodie-sweatshirt-loose-fit-fashion-pullover-hoodie-casual.json](./samples/hoodie-sweatshirt-loose-fit-fashion-pullover-hoodie-casual.json)


**Import Steps:**

1. Go to **[BC Tools](https://bc-tools.papathemes.com/)**
2. Click the **Store Manager** menu item and enter your store API key
3. Click the **Import Product** menu item
4. Select your store as the target store
5. Select **Quick Import from Samples** or Under **Product JSON File**, upload the downloaded JSON file from above
6. Click the **Import Product** button to import the product into your store

![import-product](img/import-product.png){ loading=lazy }

## Importing Widgets to Pages

To import widgets to pages (Home, Product, Cart, global regions) in your store to work exactly like our demo stores:

**Available Widget Dumps:**

- **For Man Demo Store**
    - Download: [samples/man-bc-widgets-dump.json](samples/man-bc-widgets-dump.json)

- **For Woman Demo Store**
    - Download: [samples/woman-bc-widgets-dump.json](samples/woman-bc-widgets-dump.json)

- **For Kid Demo Store**
    - Download: [samples/kid-bc-widgets-dump.json](samples/kid-bc-widgets-dump.json)

**Import Steps:**

1. Go to **[BC Tools](https://bc-tools.papathemes.com/)**
2. Click the **Store Manager** menu item and enter your store API key (skip if already entered)
3. Click the **Import Widgets** menu item
4. Select your store as the target store
5. Enter your **Channel ID** (default is `1` if you only have one storefront)
6. Click the **Load Widget Templates** button to load existing widget templates in your store
7. Select **Quick Import from Samples** or Under **Widgets JSON File**, upload the downloaded JSON file from above. After selecting the file or sample, a list of widgets and pages to be imported will appear
8. Check **"Auto-create new custom widget templates"** if you want to automatically create widget templates that are not yet available in your store but are required for our theme
9. In the **Page List**, select the pages you want to import widgets into
10. Click the **Import Widgets** button to import the widgets into your store
11. Preview your storefront with pages like Home, Product, Cart, which will look like our demo stores

![import-widgets](img/import-widgets.jpg){ loading=lazy }


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

<iframe width="760" height="515" src="https://www.youtube.com/embed/AFpgodrjqxg?si=5kDqYIO4jkK4WyX5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

To edit the background of the top header, click on Theme **Styles** > **Header**. Dinosaur theme provides users with three options to change the background by modifying the **Background Image Link** field as shown below:

- `blank`: leave the field empty, the background will be specified follow **Background color** field.

![blank-bg-img](img/blank-bg-img.jpg)

- `default`: Top header will use the default image of the theme to set as background header.

![default-bg-img](img/default-bg-img.jpg)

- `link`: Top header will be the link you provided in the input to set the background.

![link-bg-img](img/link-bg-img.jpg)

#### Quick Search

**Quick Search** allows user to change the colors of the search form.

To configure the **Quick Search**, click on **Theme Styles** > **Header**. In **Quick Search** section you can change text colors, hover, border, and background of the search field.

To change popular search keywords, type your text in **popular search keywords** field as picture below.

![header-quick-search](img/quick-search.jpg)

#### Keyword Suggestions

The keyword suggestions feature enhances the search experience by displaying popular keyword suggestions when users interact with the search box. This feature includes autocomplete functionality similar to Google Search and keyboard navigation support.

![Keyword suggestions in action](img/keyword-suggestions.jpg)

<p><iframe width="560" height="315" src="https://www.youtube.com/embed/mMg9aPb5SJY" title="Quick Search - Keyword Suggestions" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></p>


##### Quick Start

1. **Generate keywords**:
    - Go to **[BC Tools](https://bc-tools.papathemes.com/)** and click **"Keyword Extractor"** menu item
    - Enter your store URL and extract keywords (includes free credits)
    - Download the generated CSV files

2. **Upload CSV files**:
    - Upload the downloaded files to BigCommerce WebDAV `/content/` folder
    - Or upload to your own server/CDN

3. **Enable feature**:
    - Go to **Theme Editor** > **Header** > **Quick search**
    - Enable **"Enable keyword suggestions"**
    - Configure the CSV file paths
    - Save & Publish

4. **Test**: Try searching on your storefront!

##### Features

- **Smart Display**: Shows top 10 popular keywords when focusing on the search box
- **Realtime Filtering**: Updates suggestions as users type, matching keywords that start with the search query
- **Inline Autocomplete**: Like Google Search, displays suggested completion directly in the search input
    - Type "bo" → Shows "bo**ok**" with "ok" dimmed
    - Press Right Arrow (→) to accept and continue suggesting
- **Keyboard Navigation**:
    - `→` (Right Arrow): Accept autocomplete suggestion
    - `↑/↓`: Navigate between suggestions
    - `Enter`: Select highlighted suggestion
    - `Esc`: Clear selection and autocomplete
- **Responsive Design**: Adapts to mobile and desktop layouts
- **Smart Loading**: Uses lazy loading for optimal performance

##### Configuration

**Enable/Disable the Feature**

Go to **Theme Editor** > **Header** > **Quick search** section:

1. Enable **Enable keyword suggestions** checkbox
2. Configure CSV file paths (see below)
3. Save & Publish

**CSV File Configuration**

You can specify up to 3 CSV files containing keywords:

- **Keywords file 1**: Single-word keywords (e.g., "laptop", "phone")
- **Keywords file 2**: Two-word keywords (e.g., "gaming laptop", "wireless mouse")
- **Keywords file 3**: Three+ word keywords (e.g., "best gaming laptop 2024")

**File Path Options:**

You can use either relative paths or full URLs:

```
Relative path: /content/suggest-keywords-1.csv
Full URL: https://example.com/data/suggest-keywords-1.csv
```

**Note about Lazy Loading:**

- If **any** file uses a relative path, CSV files load only when users focus on search (lazy loading) - except on the search page where they load immediately
- If **all** files use full URLs, CSV files load immediately on page load
- Lazy loading reduces traffic since BigCommerce servers don't support browser cache headers

**To Disable**

**Method 1**: Uncheck "Enable keyword suggestions" in Theme Editor

**Method 2**: Leave all 3 file paths empty

##### CSV File Format

Each CSV file should have 2 columns **without a header row**:

1. **Keyword** (text)
2. **Rank** (number - **higher rank = better match, higher priority**)

**Example CSV file:**

```csv
laptop,80000
phone,70000
tablet,60000
computer,50000
monitor,40000
```

**Important:** Higher rank numbers mean the keyword will appear first in suggestions. Keywords are sorted by rank in descending order.

##### Creating CSV Files

**Method 1: Use the Keyword Extractor Tool (Recommended)**

The easiest way to create keyword CSV files is to use our **Keyword Extractor** tool:

**Step-by-step instructions:**

1. **Open BC Tools**:
    - Go to **[https://bc-tools.papathemes.com/](https://bc-tools.papathemes.com/)**
    - Click on the **"Keyword Extractor"** menu item to access the tool

2. **Extract Keywords**:
    - Enter your BigCommerce store URL in the input field
    - Click the extract button
    - The tool will automatically analyze your store's products and extract relevant keywords
    - Keywords will be organized by word count with appropriate rank values

3. **Download CSV Files**:
    - Once extraction is complete, download the generated CSV files
    - You'll typically get 3 files:
        - `suggest-keywords-1.csv` (single-word keywords)
        - `suggest-keywords-2.csv` (two-word keywords)
        - `suggest-keywords-3.csv` (three+ word keywords)

4. **Upload to Your Store**:
    - **Option A - Upload to BigCommerce WebDAV**:
        - Connect to your store via WebDAV
        - Create a `/content/` folder if it doesn't exist
        - Upload the 3 CSV files to `/content/` folder
    - **Option B - Upload to Your Own Server/CDN**:
        - Upload the CSV files to your own hosting/CDN
        - Use the full URLs in Theme Editor settings (e.g., `https://yourdomain.com/keywords/suggest-keywords-1.csv`)

5. **Configure in Theme Editor** (see Configuration section above)

This tool analyzes your actual product data and generates keyword suggestions with appropriate rank values automatically.

**Note:** The Keyword Extractor tool includes a few free credits to extract keywords. If you need to extract more keywords beyond the free credits, you'll need to purchase additional credits.

**Method 2: Create Manually**

If you prefer to create CSV files manually:

1. **Create the CSV files** on your computer using the format above
2. Use a spreadsheet program (Excel, Google Sheets) or text editor
3. Save as CSV format with 2 columns: keyword, rank (no header row)
4. Name your files:
    - `suggest-keywords-1.csv` (single-word keywords)
    - `suggest-keywords-2.csv` (two-word keywords)
    - `suggest-keywords-3.csv` (three+ word keywords)

**Then upload using one of these options:**

- **Upload to BigCommerce WebDAV**:
    - Connect to your store via WebDAV
    - Create a `/content/` folder if it doesn't exist
    - Upload the 3 CSV files to the `/content/` folder
    - Use relative paths in Theme Editor: `/content/suggest-keywords-1.csv`

- **Upload to Your Own Server/CDN**:
    - Upload to your hosting or CDN service
    - Use full URLs in Theme Editor: `https://yourdomain.com/keywords/suggest-keywords-1.csv`

After uploading, configure the file paths in **Theme Editor** > **Header** > **Quick search** section.

**Sample Data (based on actual demo data):**

**suggest-keywords-1.csv** (single words):

```csv
set,80023
usb,70042
travel,70002
new,60028
wireless,60016
original,60007
fashion,60004
men,60000
high,50044
bag,50013
phone,45000
laptop,40000
tablet,35000
computer,30000
monitor,25000
keyboard,20000
mouse,15000
camera,12000
watch,10000
shoes,8000
```

**suggest-keywords-2.csv** (two words):

```csv
micro sd,30007
high heels,30000
sd card,20010
card reader,20008
memory card,20007
gaming laptop,18000
wireless mouse,16000
bluetooth headphone,14000
mechanical keyboard,12000
usb cable,10000
running shoes,8000
smart watch,7000
leather bag,6000
phone case,5000
laptop stand,4000
```

**suggest-keywords-3.csv** (three+ words):

```csv
micro sd card,20006
breathable mesh men,20000
cotton baby hat,10001
baby hat scarf,10001
gaming laptop 2024,9000
wireless gaming mouse,8000
noise cancelling headphone,7000
mechanical keyboard rgb,6000
fast charging cable,5000
leather travel bag,4000
running shoes men,3000
smart watch women,2500
phone case clear,2000
laptop stand adjustable,1500
```

**Live Examples:** You can download actual working CSV files from the demo site:

- [suggest-keywords-1.csv](http://supermarket-yellow-demo.mybigcommerce.com/content/suggest-keywords-1.csv)
- [suggest-keywords-2.csv](http://supermarket-yellow-demo.mybigcommerce.com/content/suggest-keywords-2.csv)
- [suggest-keywords-3.csv](http://supermarket-yellow-demo.mybigcommerce.com/content/suggest-keywords-3.csv)

##### How It Works

1. **On Page Load**:
    - If using full URLs: CSV files load with low priority (doesn't block page)
    - If using relative paths: Waits until user focuses on search box (or on search page)

2. **On Search Focus**: Displays top 10 keywords sorted by rank

3. **While Typing**:
    - Filters keywords that **start with** the typed text
    - Shows inline autocomplete suggestion (first match)
    - Updates in realtime (debounced 100ms)

4. **Selecting Keyword**: Fills the search box and triggers quick search

##### Advanced Configuration

For advanced users who want to use external CDN or customize file paths, you can:

1. Upload CSV files to your own CDN
2. Use full URLs in the Theme Editor settings
3. This enables immediate loading with browser caching support

**Example with CDN:**

```
Keywords file 1: https://cdn.yourstore.com/keywords/single-words.csv
Keywords file 2: https://cdn.yourstore.com/keywords/two-words.csv
Keywords file 3: https://cdn.yourstore.com/keywords/three-words.csv
```

##### Tips for Best Results

1. **Use the Keyword Extractor Tool**: Start with our **[Keyword Extractor](https://bc-tools.papathemes.com/)** to automatically generate keywords from your actual products - this is the fastest and most accurate way
2. **Rank Keywords by Popularity**: Assign higher rank numbers to more popular search terms (e.g., "laptop,80000" appears before "mouse,15000")
3. **Use Meaningful Rank Gaps**: Leave gaps between ranks (e.g., 80000, 70000, 60000) so you can easily insert new keywords later
4. **Organize by Word Count**: Use the 3 files to separate keywords by length for better matching:
    - File 1: Single words ("laptop", "phone")
    - File 2: Two words ("gaming laptop", "wireless mouse")
    - File 3: Three+ words ("best gaming laptop 2024")
5. **Base on Search Analytics**: Use your store's actual search data to identify popular keywords
6. **Update Regularly**: Refresh your keyword lists based on seasonal trends and new products
7. **Start Small**: Begin with 20-30 keywords per file and expand as needed
8. **Test Thoroughly**: After uploading CSV files, test on different devices to ensure smooth performance
9. **Match Your Products**: Include keywords that actually match products in your store

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

To customize Banner on bottom of sub menu on mobile. Drag and drop **Flex Banners | PapaThemes Beautify** into corresponding position:

![edit-widget-megamenu](img/edit-flex-banner-bottom.jpg)

In **Column 1**, set padding = `0`.

Click **Settings** of **Flex Banners | PapaThemes Beautify**. In `Row wrap`, choose `Row no wrap on table` and `Row no wrap on mobile`.

![edit-widget-megamenu](img/edit-flex-banner-bottom-wrap.jpg)

Remove all banner except banner 1. Selet your image want to upload. Set `Image width` = `350px`, `Image height` = `209px`. Set `Border radius` = `0px`.

In **CONTENT**, hide `Heading text`.

![edit-widget-megamenu](img/edit-setting-flex-banner.jpg)

Duplicate 1 banner to 2 banners.

To hide on desktop and show on mobile. Drag and drop **Responsive | PapaThemes** on top **Flex Banners | PapaThemes Beautify** created.

In **Screen Size 1**. Set `Max` = `800px` and set `Display` = `Show`.

In **Screen Size 2**. Set `Min` = `801px` and `Max` = `0px`. Set `Display` = `Hide`.

![edit-widget-megamenu](img/edit-flex-banner-response.jpg)


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

**Watch the instruction video:**

<iframe width="760" height="515" src="https://www.youtube.com/embed/8gJ2qS92AUg?si=zJJ9CwFmVu0Jk1HQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; pictre-in-picture; web-share" allowfullscreen></iframe>

### Top Banner

Go back to **Storefront** > **My Themes** > click **Customize** button beside the theme thumbnail. You can see the top banner appears above the header. To change the colors of the top banner, go to **Theme Styles** > **General** > **Top banners** section. Here you can change the text color and the background color.

**Watch the instruction video:**

<iframe width="760" height="515" src="https://www.youtube.com/embed/NL1QiC3INpU?si=oMcyYeScMlBQl28f" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


You can also create **top banner** by drag and drop **HTML widget** into corresponding position:

![top-banner](img/top-banner.jpg)

Enter your content inside `<p></p>`.

```html
<p>Get a discount with our limited time offer - Use code&nbsp;<strong>SAVE10</strong>&nbsp;for&nbsp;<strong>10%</strong>&nbsp;off your purchase!</p>
<p>Dive into our newest collection of eco-friendly products! Let's make a difference together.</p>
<p>Discover the beauty of handcrafted artisanal items in our latest collection. Every piece tells a story.</p>

```

### Ad Banner Top header

To display the ad banner appearing on all pages on the header, drag and drop the HTML widget to the corresponding position, paste the given code below to the HTML editor, then click Save HTML button.

```html
<p>STAY AHEAD OF THE STYLE CURVE WITH OUR LATEST ARRIVALS -<a href="/shipping-returns/" style="font-weight: 500"> Discover Now</a></p>
```

**Watch the instruction video:**

<iframe width="760" height="515" src="https://www.youtube.com/embed/bxD_I4ZbMi0?si=b9dDgPVcNsiazSX5" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; pictre-in-picture; web-share" allowfullscreen></iframe>

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

<iframe width="760" height="515" src="https://www.youtube.com/embed/IvW6T-P3Oxs?si=vGlWYu6UDo4n11HP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; pictre-in-picture; web-share" allowfullscreen></iframe>

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

`Return & Exchange`:

![policy-delivery-hotline](img/return&exchange.png)

```html
<svg width="41" height="41" viewBox="0 0 41 41" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M20.5 8.45103C13.8561 8.45103 8.45103 13.8562 8.45103 20.5C8.45103 27.1438 13.8561 32.549 20.5 32.549C27.1438 32.549 32.5489 27.1438 32.5489 20.5C32.5489 13.8561 27.1438 8.45103 20.5 8.45103ZM20.5 30.1466C15.1808 30.1466 10.8534 25.8191 10.8534 20.5C10.8534 15.1809 15.1808 10.8534 20.5 10.8534C25.8192 10.8534 30.1466 15.1808 30.1466 20.5C30.1466 25.8192 25.8192 30.1466 20.5 30.1466Z" fill="#C72E2E"/>
<path d="M19.701 18.9634C19.701 18.6952 19.9469 18.4718 20.7179 18.4718C21.3995 18.4718 22.1258 18.6617 22.8968 19.0528L23.6902 17.1421C23.0533 16.7844 22.2487 16.5722 21.4218 16.4939V15.2983H19.8463V16.5163C18.0137 16.7732 17.0975 17.8348 17.0975 19.0975C17.0975 22.0139 21.4218 21.2206 21.4218 22.2039C21.4218 22.4721 21.1537 22.6285 20.405 22.6285C19.5446 22.6285 18.5613 22.3492 17.8238 21.9134L16.9745 23.8353C17.645 24.2488 18.7289 24.5505 19.8463 24.6175V25.802H21.4218V24.5617C23.1538 24.26 24.0254 23.2096 24.0254 22.0028C24.0254 19.1198 19.701 19.902 19.701 18.9634Z" fill="#C72E2E"/>
<path d="M40.8782 18.2724L38.4887 18.5365C38.9355 22.5788 37.9786 26.7111 35.7943 30.1722C33.5796 33.6811 30.1889 36.3408 26.2464 37.6614C24.359 38.2935 22.4202 38.5964 20.4999 38.5962C14.9568 38.5959 9.57724 36.0708 6.10081 31.6574H8.48105V29.2533H2.05302V35.9775H4.45713V33.4453C6.74961 36.2366 9.78777 38.4132 13.2372 39.6973C15.568 40.565 18.0268 41 20.4825 41C22.6928 41 24.9007 40.6475 27.0099 39.941C31.4761 38.445 35.3178 35.4314 37.8271 31.4554C40.3011 27.5356 41.3847 22.8538 40.8782 18.2724ZM5.12106 10.9781C7.33546 7.40032 10.7563 4.69256 14.7534 3.35358C18.6459 2.04982 22.7407 2.09122 26.5955 3.47369C29.6057 4.55331 32.2894 6.42754 34.3366 8.84894L32.0456 8.84814L32.0448 11.2522L38.5441 11.2544V4.83094H36.14V7.25931C33.825 4.53553 30.7989 2.42715 27.4071 1.21068C23.0392 -0.355725 18.3995 -0.403051 13.9899 1.07399C9.46177 2.59075 5.58615 5.65879 3.0769 9.71282C0.600326 13.7142 -0.433323 18.4739 0.166302 23.1151L2.55055 22.807C2.02147 18.712 2.93436 14.5111 5.12106 10.9781Z" fill="#C72E2E"/>
</svg>
```

`Quality guarantee`:

![policy-delivery-hotline](img/quality.png)

```html
<svg width="35" height="41" viewBox="0 0 35 41" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M17.5 0L0 6.36899V20.5255C0 36.521 16.9823 40.873 17.1529 40.9168L17.5 41L17.8471 40.9168C18.0177 40.873 35 36.521 35 20.5255V6.36899L17.5 0ZM32.0833 20.5255C32.0833 33.192 19.8188 37.3193 17.5058 37.9848C15.2746 37.3237 2.91667 33.0826 2.91667 20.5255V8.4122L17.5 3.10569L32.0833 8.4122V20.5255Z" fill="#C72E2E"/>
<path d="M9.78104 19.4937L7.71896 21.5574L14.5833 28.4269L27.281 15.7196L25.219 13.656L14.5833 24.2997L9.78104 19.4937Z" fill="#C72E2E"/>
</svg>
```

`Free Delivery`:

![policy-delivery-hotline](img/free-delivery.png)

```html
<svg width="58" height="39" viewBox="0 0 58 39" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M57.3706 18.2462L53.8576 14.985C53.6181 14.7627 53.4344 14.487 53.3215 14.1802L50.5627 6.68298C50.1681 5.62638 49.4612 4.71521 48.5361 4.07091C47.611 3.42661 46.5116 3.07978 45.3846 3.07665H41.2046V1.90306C41.2046 1.39837 41.0043 0.914341 40.6477 0.557466C40.2911 0.200591 39.8075 0.000100328 39.3032 0.000100328H14.0416C13.6658 -0.00433001 13.303 0.13812 13.0304 0.397171C12.7578 0.656222 12.597 1.01145 12.582 1.38734C12.5785 1.57524 12.6124 1.76196 12.6818 1.93657C12.7513 2.11119 12.8548 2.27021 12.9863 2.40434C13.1178 2.53847 13.2748 2.64501 13.4479 2.71775C13.6211 2.79049 13.807 2.82796 13.9947 2.82797H38.3789V15.0973C38.3789 15.602 38.5792 16.086 38.9358 16.4429C39.2924 16.7998 39.776 17.0003 40.2803 17.0003H51.7636L55.1741 20.072V31.5302H52.0822C51.7743 30.1819 51.0182 28.9781 49.9376 28.1159C48.857 27.2537 47.5159 26.7841 46.1339 26.7841C44.7519 26.7841 43.4108 27.2537 42.3302 28.1159C41.2496 28.9781 40.4934 30.1819 40.1855 31.5302H30.6712C30.3633 30.1819 29.6072 28.9781 28.5266 28.1159C27.4459 27.2537 26.1049 26.7841 24.7228 26.7841C23.3408 26.7841 21.9998 27.2537 20.9191 28.1159C19.8385 28.9781 19.0824 30.1819 18.7745 31.5302H14.0415C13.6656 31.5258 13.3028 31.6683 13.0302 31.9274C12.7577 32.1865 12.5968 32.5418 12.582 32.9178C12.5785 33.1057 12.6124 33.2924 12.6818 33.467C12.7513 33.6416 12.8548 33.8006 12.9863 33.9348C13.1178 34.0689 13.2748 34.1754 13.4479 34.2481C13.6211 34.3209 13.807 34.3583 13.9947 34.3583H18.7983C19.1255 35.6832 19.8868 36.8602 20.9606 37.7015C22.0343 38.5429 23.3587 39 24.7225 39C26.0862 39 27.4106 38.5429 28.4843 37.7015C29.5581 36.8602 30.3194 35.6832 30.6466 34.3583H40.2096C40.5368 35.6832 41.2981 36.8602 42.3718 37.7015C43.4456 38.5429 44.77 39 46.1337 39C47.4974 39 48.8218 38.5429 49.8956 37.7015C50.9694 36.8602 51.7306 35.6832 52.0579 34.3583H56.0985C56.6028 34.3583 57.0864 34.1578 57.443 33.801C57.7996 33.4441 58 32.9601 58 32.4555V19.6605C57.9998 19.3938 57.9437 19.1301 57.8353 18.8865C57.7269 18.6429 57.5686 18.4248 57.3706 18.2462ZM41.2046 14.1728V5.9044H45.3846C45.9349 5.90591 46.4717 6.07524 46.9234 6.38983C47.375 6.70442 47.7202 7.14932 47.9128 7.66523L50.3212 14.1728H41.2046ZM24.7225 36.1717C24.0743 36.1717 23.4407 35.9794 22.9017 35.619C22.3628 35.2586 21.9427 34.7463 21.6947 34.147C21.4466 33.5476 21.3817 32.8882 21.5082 32.2519C21.6347 31.6157 21.9468 31.0313 22.4051 30.5726C22.8635 30.1139 23.4475 29.8015 24.0832 29.675C24.719 29.5484 25.3779 29.6134 25.9768 29.8616C26.5756 30.1099 27.0874 30.5303 27.4475 31.0697C27.8076 31.6091 27.9998 32.2432 27.9998 32.8919C27.9988 33.7615 27.6532 34.5952 27.0388 35.21C26.4244 35.8249 25.5914 36.1708 24.7225 36.1717ZM46.1338 36.1717C45.4856 36.1717 44.8519 35.9794 44.313 35.619C43.774 35.2586 43.3539 34.7464 43.1058 34.147C42.8578 33.5477 42.7929 32.8882 42.9193 32.252C43.0458 31.6157 43.3579 31.0313 43.8163 30.5726C44.2746 30.1139 44.8586 29.8015 45.4943 29.675C46.1301 29.5484 46.789 29.6134 47.3879 29.8616C47.9867 30.1099 48.4986 30.5303 48.8587 31.0697C49.2188 31.6091 49.411 32.2432 49.411 32.8919C49.41 33.7615 49.0644 34.5951 48.45 35.21C47.8356 35.8249 47.0026 36.1707 46.1338 36.1717Z" fill="#C72E2E"/>
<path d="M7.96133 10.7384H23.9842C24.3589 10.7384 24.7183 10.5894 24.9833 10.3242C25.2483 10.059 25.3972 9.69932 25.3972 9.32427C25.3972 8.94923 25.2483 8.58955 24.9833 8.32435C24.7183 8.05916 24.3589 7.91017 23.9842 7.91017H7.96133C7.58659 7.91017 7.22719 8.05916 6.9622 8.32435C6.69721 8.58955 6.54835 8.94923 6.54835 9.32427C6.54835 9.69932 6.69721 10.059 6.9622 10.3242C7.22719 10.5894 7.58659 10.7384 7.96133 10.7384ZM25.3972 17.1793C25.3972 16.8042 25.2483 16.4445 24.9833 16.1793C24.7183 15.9141 24.3589 15.7652 23.9842 15.7652H1.42564C1.23903 15.7635 1.05393 15.7988 0.881039 15.8691C0.708148 15.9395 0.550888 16.0433 0.418337 16.1748C0.285787 16.3063 0.180573 16.4627 0.108771 16.6351C0.0369685 16.8075 0 16.9924 0 17.1792C0 17.366 0.0369685 17.5509 0.108771 17.7233C0.180573 17.8957 0.285787 18.0521 0.418337 18.1836C0.550888 18.3151 0.708148 18.419 0.881039 18.4893C1.05393 18.5596 1.23903 18.5949 1.42564 18.5932H23.9842C24.3589 18.5932 24.7183 18.4443 24.9833 18.1791C25.2483 17.9139 25.3971 17.5543 25.3972 17.1793ZM16.4505 25.0342C16.4505 24.8486 16.4139 24.6647 16.3429 24.4931C16.2719 24.3216 16.1679 24.1657 16.0367 24.0344C15.9055 23.9031 15.7497 23.7989 15.5783 23.7279C15.4069 23.6568 15.2231 23.6203 15.0376 23.6203H5.21701C4.84447 23.6236 4.48832 23.774 4.22607 24.0389C3.96381 24.3037 3.81668 24.6615 3.81668 25.0343C3.81668 25.4072 3.96381 25.7649 4.22607 26.0297C4.48832 26.2946 4.84447 26.445 5.21701 26.4483H15.0376C15.4123 26.4483 15.7717 26.2993 16.0367 26.0341C16.3016 25.7689 16.4505 25.4093 16.4505 25.0342Z" fill="#C72E2E"/>
</svg>
```

`Hot line`:

![policy-delivery-hotline](img/hotline.png)

```html
<svg width="48" height="42" viewBox="0 0 48 42" fill="none" xmlns="http://www.w3.org/2000/svg">
<path d="M41.5216 14.7448C41.133 10.8471 39.2884 7.2309 36.3461 4.59853C33.4038 1.96616 29.5738 0.505582 25.6 0.500488H22.4C18.4262 0.505582 14.5962 1.96616 11.6539 4.59853C8.71155 7.2309 6.86696 10.8471 6.4784 14.7448C4.72187 14.8701 3.07825 15.645 1.87687 16.9141C0.675491 18.1833 0.00509204 19.853 0 21.5887V26.72C0.00211736 28.5483 0.739958 30.301 2.05165 31.5938C3.36335 32.8866 5.14178 33.6138 6.9968 33.6159H11.2C11.6243 33.6159 12.0313 33.4497 12.3314 33.154C12.6314 32.8583 12.8 32.4572 12.8 32.039V16.2697C12.8 15.8515 12.6314 15.4504 12.3314 15.1547C12.0313 14.8589 11.6243 14.6928 11.2 14.6928H9.7104C10.1025 11.647 11.6071 8.84626 13.9427 6.81458C16.2782 4.78291 19.2848 3.65944 22.4 3.65433H25.6C28.7152 3.65944 31.7218 4.78291 34.0573 6.81458C36.3929 8.84626 37.8975 11.647 38.2896 14.6928H36.8C36.3757 14.6928 35.9687 14.8589 35.6686 15.1547C35.3686 15.4504 35.2 15.8515 35.2 16.2697V32.039C35.2 32.4572 35.3686 32.8583 35.6686 33.154C35.9687 33.4497 36.3757 33.6159 36.8 33.6159H38.1728C37.8191 34.9659 37.0215 36.1625 35.9047 37.0184C34.7879 37.8743 33.4147 38.3414 32 38.3466H28.8V36.7697C28.8 36.3515 28.6314 35.9504 28.3314 35.6547C28.0313 35.3589 27.6243 35.1928 27.2 35.1928C26.7757 35.1928 26.3687 35.3589 26.0686 35.6547C25.7686 35.9504 25.6 36.3515 25.6 36.7697V39.9236C25.6 40.3418 25.7686 40.7429 26.0686 41.0386C26.3687 41.3344 26.7757 41.5005 27.2 41.5005H32C34.2749 41.4979 36.4749 40.6992 38.2079 39.2468C39.9409 37.7944 41.0943 35.7826 41.4624 33.5701C43.2303 33.4582 44.889 32.6884 46.1028 31.4166C47.3166 30.1448 47.9947 28.466 48 26.72V21.5887C47.9949 19.853 47.3245 18.1833 46.1231 16.9141C44.9217 15.645 43.2781 14.8701 41.5216 14.7448ZM9.6 30.462H6.9968C5.99009 30.4612 5.02485 30.0667 4.31299 29.3651C3.60114 28.6635 3.20085 27.7122 3.2 26.72V21.5887C3.20085 20.5965 3.60114 19.6452 4.31299 18.9436C5.02485 18.242 5.99009 17.8475 6.9968 17.8466H9.6V30.462ZM44.8 26.72C44.7992 27.7122 44.3989 28.6635 43.687 29.3651C42.9752 30.0667 42.0099 30.4612 41.0032 30.462H38.4V17.8466H41.0032C42.0099 17.8475 42.9752 18.242 43.687 18.9436C44.3989 19.6452 44.7992 20.5965 44.8 21.5887V26.72Z" fill="#C72E2E"/>
</svg>
```

Select `Custom` for the **Text style**. In **Font weight** select `Bold`. Customize the text content and choose your preferred Text color.

Enable **Show text**, to display fist text right below the icon. Select `Custom` for the **Text style ** . Set the **Font size** = `16px` for desktop devices. Adjust the **Font size(Mobile)** = `10px`. Customize the text content and choose your preferred Text color

![policy-delivery-first-text](img/policy-delivery-first-text.jpg)

Enable **Show second text**, to display second text. Select `Custom` for the **Second text style**. Set the **Font size** = `14px` for desktop devices. Adjust the **Font size(Mobile)** = `10px`. Customize the text content and choose your preferred Text color.

To make the text color lighter, click on **Text color** then click `+` icon, choose your desired color and in section `A`, adjust to 0.6 to make the text lighter.

![policy-delivery-second-text](img/policy-delivery-second-text.jpg)

Duplicate callout 1, 3 times to create 3 similar icons. Change the image and link of the icons just created.

Watch the instruction video:

<iframe width="760" height="515" src="https://www.youtube.com/embed/OBCNgKE6GPQ?si=CUJp8nHvLZgJhbik" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; pictre-in-picture; web-share" allowfullscreen></iframe>

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

![Top-categories](img/top-categories.jpg)

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

**Watch the instruction video:**

<iframe width="760" height="515" src="https://www.youtube.com/embed/Kq7EcW4wAmQ?si=k2_EUcsCyJubNkRF" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; pictre-in-picture; web-share" allowfullscreen></iframe>

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

**Watch the step-by-step setup video:**

<div style="position: relative; padding-bottom: 80.59701492537313%; height: 0;"><iframe src="https://www.loom.com/embed/18daf9bc2f664ee28e8f26a43c926c20?sid=4f2b7361-913e-449f-ac7e-128b1b51a9eb" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>

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

**Watch the instruction video:**

<iframe width="760" height="515" src="https://www.youtube.com/embed/CKuhCOSMPR4?si=HomGPI60tzLj5bQD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>



### Newsletter

![edit-newsletter](img/edit-newsletter.jpg)

To enable newsletter form, go to **Marketing** > **Email Marketing**, make sure **Allow Newsletter Subscriptions** is checked. Optionally select **Show Newsletter Summary** and enter the summary text as you want.

Go to Page Builder, in **Theme Styles** > **Footer** > **Newsletter** section.

Make sure **Show newsletter form** is selected. You can change the **Heading**, **background color**, **background image**, **button** and **text colors**.

**Watch the instruction video:**

<iframe width="760" height="515" src="https://www.youtube.com/embed/K25Fthor0jE?si=LcO3xJm3V_f8-HAt" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

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

<iframe width="760" height="515" src="https://www.youtube.com/embed/qIK4uCQxIJ8?si=yqS1NXihsqslwgV3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


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

<iframe width="760" height="515" src="https://www.youtube.com/embed/iUCG6iXI0zg?si=MMQGRbdEEY3D6KBP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Display Custom Footer Links

In **Page builder** > **Custom Widget** find **Footer links | PapaThemes Beautify** widget then drag and drop the widget to corresponding position in **Footer**.

Select the **Column 1** and change **padding** to `0 0 0 0`.

In **design** you can type your link content and click on the **insert/edit link** button as picture below:

![footer-links](img/footer-link-widget.jpg)

In the popup window, copy your web link to `URL`. On the **Open links..** field you can select how your link could be open in **New Window** or **Current Window**

 ![Insert-links](img/insert-links.jpg)


## Setting Up Woman Style Home Page

### General

You can read these common instructions in **Setting Up Man Style Home Page** chapter:

- [Header](#header)
- [Top Banner](#top-banner)
- [Ad Banner displays on all pages](#ad-banner-top-header)
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

- [Homepage Left Sidebar Layout](#homepage-left-sidebar-layout)
- [Homepage Left Sidebar Banner](#homepage-left-sidebar-banner)
- [Homepage Customer Reviews Left Sidebar](#homepage-customer-reviews-left-sidebar)
- [Homepage About Us Left Sidebar](#homepage-about-us-left-sidebar)
- [Header](#header)
- [Top Banner](#top-banner)
- [Ad Banner displays on all pages](#ad-banner-top-header)
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

### Homepage Left Sidebar Layout

![Left Sidebar](img/left-sidebar-img.jpg)

To display the left sidebar on the home page, go to **Page Builder**. In **Theme Styles** > **Home Page** > **Left Sidebar**, ensure that at least one of the three options is filled in. You can also change the order of each section by section name as below:

- `popular_producs`: to display best seller products
- `new_products`: to display new arrival products
- `featured_products`: to display feature producs.

![Left Sidebar](img/left-sidebar-settings.jpg)

Note: Leftside bar can only display three section above. To modify the header or configure each section, kindly scroll down to the specific section configuration you wish to alter.

**Watch the instruction video:**

<iframe width="760" height="515" src="https://www.youtube.com/embed/8gpBh4eSM90?si=zUAJFNSdIzfX1kNP" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; pictre-in-picture; web-share" allowfullscreen></iframe>

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

**Watch the instruction video:**

<iframe width="760" height="515" src="https://www.youtube.com/embed/IPmMqh3xJN0?si=hUpUiQGEYsysF8IS" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; pictre-in-picture; web-share" allowfullscreen></iframe>

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

Drag & drop **HTML** widget below **Text** widget. Enter follow code to create read more button:

**Watch the instruction video:**

<iframe width="760" height="515" src="https://www.youtube.com/embed/LQfMYvQbykg?si=ObcCnReuSzbPVDu-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; pictre-in-picture; web-share" allowfullscreen></iframe>

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

### Displaying product tabs description full width

In **Page Builder** > **Theme Styles** > **Products** > **Product Page**:

- Tick **Tab description full width** checkbox to display tabs description full width in Product page.

![Tabs-fullwidth](img\product-tabs-fullwidth.jpg)

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

![shipping-countdown](img/shipping-countdown.jpg)

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

**Watch the instruction video:**

<iframe width="760" height="515" src="https://www.youtube.com/embed/TFaHUPuuzKg?si=8LjKIj4aHZkS4fFR" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; pictre-in-picture; web-share" allowfullscreen></iframe>

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


### Product Designer Tool

The Product Designer Tool allows customers to customize product designs directly on your website. When enabled, customers can create custom designs that will be packaged and attached to their order.

![Product Designer Tool](img/product-designer-tool.jpg)

**Setting Up Product Designer Tool:**

#### 1. Configure in Theme Editor

   - Navigate to **Theme Editor** > **Products** > **Product Page**
   - Find **Product Designer Modifier Name** field
   - Enter the exact name of your modifier, for example: `"Design File"`
   - **Important:** The modifier name must match exactly (case-sensitive)

   ![Product Designer Tool Configuration](img/theme-editor-product-designer-modifier.jpg)

#### 2. Create Product Modifier

   - Go to your product settings
   - Create a new modifier with the exact name you configured above (e.g., "Design File")
   - Set modifier type to **File**
   - Enable support for **.zip** file format
   - This modifier will store the customer's design files

   ![Add Design File Modifier](img/add-design-file-modifier.jpg)

#### 3. How It Works

   - After configuration, products with the "Design File" modifier will display a **Customize Design** button on the Product Details page
   - Customers can click this button to access the design tool
   - Once customers complete their design, all design files are packaged into a Zip file
   - The packaged file is automatically attached to the product when added to cart

**Note:** Only products that have the configured modifier will show the Customize Design button. Make sure to add the modifier to all products that need design customization capability.


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

<iframe width="760" height="515" src="https://www.youtube.com/embed/T_V5ESUEq2M?si=GvRIRsv8OkWSS6gQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; pictre-in-picture; web-share" allowfullscreen></iframe>

### Display product in Search page

To change number products display per page in **Product** section find **Search page** then change **Number of products per page**:

![Search-product-number](img/product-search-page.jpg)

## Customizing Cart page

### Display free shipping message in cart page.

Not qualify message

![Not-qualify](img/not-egilible.jpg)

Qualify message

![qualify](img/promotion-qualify.jpg)

In **Marketing** > **Promotion** click on **create** and select **With legacy editor**

In **Promotion detail** name your promotion

In **promotion type** select `Orders totaling more than X amount get free shipping to specific shipping zones` at the field **spend at least** type your amount

![free-shipping-editor](img/free-shipping.jpg)

In **Promotion option** type your message at **Congratulations Banner Message** to display for cart have qualified and type your message for cart have not qualify at **Upsell Banner Message** with format `[your text] %%condition.remaining%% [your text]` then click save

![promotion-message](img/Promotion-message.jpg)

## Customize Design

![customize-design-general](img/customize-design-general.jpg)

### Configuration

- Inside the Page Builder, go to: `Theme Styles` → `Products` → `Product Designer Modifier Name`, then enter **“Design File”** into this field.

![customize-design-pb-setting](img/customize-design-PB-setting.jpg)

- ⚠️ If this field is left **empty**, the Customize Design feature will be automatically **disabled**.

To activate **Customize Design** for a product, create a Product **Modifier** with:

- **Name** that **matches exactly** the value set in `Product Designer Modifier Name`.

- **Type** set to `File Upload`

- Set the **Maximum File Size** within the system **limit of 524,288 KB** (For example, we recommend using 51,200 KB for optimal performance.)

- Set **File Types** as: Select `Only allow certain file types to be uploaded`, Choose `Other file types`, Enter `ZIP` to allow only ZIP file.

![customize-design-product-modifier-detail](img/customize-design-product-modifier-detail.jpg)

### How to find Design file in order

**Design Data Attached to the Order**

- After the customer finishes designing, adds the product to the cart, and successfully completes checkout, the system will automatically attach the **design file** to the order.
This file contains all design information, including: `Customer-uploaded images`, `All added texts`, `Complete design layout data`.

**Download Design File in Order Management**

- In the **Store Manager**, open the **Order Detail** page.

- Locate the section whose name **matches** the value set in the **“Product Designer Modifier Name”** field in the `Page Builder`.

- Click on `design.zip` to **download** the product’s design file to your device.

![customize-design-order](img/customize-design-order.jpg)

**Use Design Data for Production**

- Inside the downloaded `design.zip` file, all original design data will be stored, including: `Design structure`, `Uploaded images`, `Customer texts`.

![customize-design-file-1](img/customize-design-file-1.jpg)

![customize-design-file-2](img/customize-design-file-2.jpg)