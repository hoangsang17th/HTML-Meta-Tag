## Definition and Usage 
The <meta> tag defines metadata about an HTML document. Metadata is data (information) about data.

<meta> tags always go inside the <head> element, and are typically used to specify character set, page description, keywords, author of the document, and viewport settings.

Metadata will not be displayed on the page, but is machine parsable.

Metadata is used by browsers (how to display content or reload page), search engines (keywords), and other web services.

There is a method to let web designers take control over the viewport (the user's visible area of a web page), through the <meta> tag (See "Setting The Viewport" example below).
## Basic HTML Meta Tags

``` html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<!-- Setting the viewport to make your website look good on all devices -->
<title> Meta tag | Hoàng Sang </title>
<!-- Your page title -->
<meta name="description" content="About 150 characters"/>
<!-- Define a description of your web page -->
<meta name="keywords" content="HoangSang17Th, Meta Html, Github"/>
<!-- Define keywords for search engines -->
<meta name="author" content="Hoàng Sang">
<!-- Author's Name -->
<meta name="copyright"content="Copyright © 2021 Hoàng Sang, All rights reserved.">
<!-- The Copyright tag records information of who copyright ownership belongs to. -->
<meta name="distribution" content="Global">
<!-- This meta tag defines the level or degree of distribution of your web-page -->
<meta name="language" content="Vi">
<!-- Abbreviation for the language used in the web -->
<meta name= "News_Keywords" content="">
<!-- help Google News better understand the nature of your content -->
<meta name="robots" content="index,follow" />
<!-- All search engines -->
<meta name="robots" content="index,follow" />
<!-- All search engines -->
 <meta name="theme-color" content="#2c3e50">
<!-- Theme Color for Chrome, Firefox OS và Opera -->
<meta name="topic" content="Introduction to meta tags">
<!-- Topic of website -->
<meta name="summary" content="">
<!-- A summary of the site's content -->
<meta name="Classification" content="Business">
<meta name="rating" content="General">
<!-- If you wish to rate your page’s audience appropriateness, use the rating meta tag. -->
<meta http-equiv="Cache-Control" content="no-cache">
<!-- The meta cache control tag allows Web publishers to define how pages should be handled by caches -->
<meta http-equiv="Expires" content="0">
<!-- The html meta tag HTTP-EQUIV CONTENT-TYPE allows you to specify the media type (i.e. text/html) and the character set. -->
<meta http-equiv="Imagetoolbar" content="0">
<!-- This tag was used to facilitate how to handle images and photos when you use Internet Explorer.  (IE6) -->
<meta name = "referrer" content = "no-referrer">
<!-- Disable automatic detection and format of phone numbers that may exist on the web -->
```

## OpenGraph Meta Tags

``` html
<meta name="og:title" content="Hoàng Sang"/>
<meta name="og:type" content="share code"/>
<meta name="og:url" content="https://github.com/hoangsang17th/"/>
<meta name="og:image" content="https://raw.githubusercontent.com/hoangsang17th/sit-php/master/Logo.png"/>
<meta name="og:site_name" content="HoangSang17Th"/>
<meta name="og:description" content="My name's Phạm Hoàng Sang"/>
<meta name="fb:page_id" content="624988424767104" />
<meta name="og:street-address" content="Trần Đại Nghĩa, Ngũ Hành Sơn"/>
<meta name="og:locality" content="Đà nẵng, Việt Nam"/>
<meta name="og:region" content="DA"/>
<meta name="og:postal-code" content="550000"/>
<meta name="og:country-name" content="VN"/>

<meta property="og:type" content="education"/>
<meta property="og:points" content="POINTS_FOR_ACHIEVEMENT"/>
<meta property="og:video" content="https://www.youtube.com/watch?v=kjQhtf1TfRk" />
<meta property="og:video:height" content="1920" />
<meta property="og:video:width" content="1080" />
<meta property="og:video:type" content="application/x-shockwave-flash" />
```   
## HTML Link Tags

``` html
<link rel="alternate" hreflang="en-gb" href="http://en-gb.example.com/page.html" />
<link rel="alternate" hreflang="en-us" href="http://en-us.example.com/page.html" />
<link rel="alternate" hreflang="en" href="http://en.example.com/page.html" />
<link rel="alternate" hreflang="de" href="http://de.example.com/page.html" />
<link rel="alternate" hreflang="x-default" href="http://www.example.com/" />
<!-- It would direct US, UK, generic English speakers, and German speakers to localized pages, and all others to a generic homepage. Google Search returns the appropriate result for the user, according to their browser settings. -->
<link rel="shortcut icon" type="image/ico" href="/favicon.ico" />
<!-- A favicon is a graphic image (icon) associated with a particular Web page and/or Web site -->
<link rel="fluid-icon" type="image/png" href="/fluid-icon.png" />
<!-- Fluid is a way of running web applications as if they were native Mac apps. The fluid icon is the one that displays on the Mac in the dock. -->
```

## About Author
* [Phạm Hoàng Sang](https://www.facebook.com/HoangSang17TH/) - VKU
* Email: Phsang49@gmail.com
* [Youtube](https://www.youtube.com/channel/UCFovmhE6wmj-6doJKKURaiA)
* Author support: MB Bank 5050148454917
