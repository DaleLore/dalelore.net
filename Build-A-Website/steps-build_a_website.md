# REMINDERS ON THE BASICS: HOW TO BUILD A WEBSITE

## What you need
##### 1. [Web Hosting](#🏠-Web-Hosting)
##### 2. [Domain Registration](#📭-Domain-Registration)
##### 3. [Website](#🎨-Website-Design)
* [HTML: HyperText Markup Language](#HTML:-HyperText-Markup-Language)
* [CSS: Cascading Style Sheets](#CSS:-Cascading-Style-Sheets)


## Step up
### 🏠 Web Hosting
Leasing the 'house': Web hosting is where your website will ‘live’. It’s basically a computer where people store their websites. There are different types of web hosting (shared, virtual private servers, dedicated, and cloud hosting), but shared hosting services are common and usually cheaper.

NOTE: You CAN have a web hosting provider without a domain name. Web hosting providers will just use their own URL addresses (i.e: .wix.com, .wordpress.org, etc). A unique domain name will look more professional and promote YOU rather than the web hosting provider.

NOTE: You can buy the domain and web hosting together. Some companies like Wix and Squarespace do that. If you do them separately, you will have to set up an alias redirection from your domain name to your web hosting provider, but there are more benefits having them separated compared to the convenience of buying them packaged together.
Sign up for a web hosting plan
This depends on money and how comfortable you feel on the platform. A platform that has a lot of documentation (from other users. Not just the service), is always helpful.
Web hosts automatically give you a domain name too, but it usually will have the service name somewhere in the URL.


#### ☑️ Sign up for a web hosting plan 💸
  * This depends on money and how comfortable you feel on the platform. A platform that has a lot of documentation (from other users. Not just the service), is always helpful.
  * Web hosts automatically give you a domain name too, but it usually will have the service name somewhere in the URL.

#### ☑️ (Optional) Prep your web hosting provider for the domain name set up
  * Depending on which platform you choose, you’ll need to “warn” your platform in the settings that something is going to be redirected to it.

#### ☑️  What web hosting services are available? 🤔

| “Free” Hosts   | Paid Hosts/ Website Builders | Both Host and Domain |
| -------------- | ---------------------------- | -------------------- |
| GitHub Pages   | Wordpress.org*               | SquareSpace          |
| Google Sites   | SquareSpace                  | Wix                  |
| Wordpress.com* | Weebly                       |                      |
|                |   Wix                           |                      |


*Yes. WordPress.com and WordPress.org are different. I know  😖



### 📭 Domain Registration
Leasing or buying the ‘address’: The domain name is the website address. These are websites that you plug into your browser that usually end with .com, .net, .io, etc.

NOTE: You can buy the domain and web hosting together. Some companies like Wix and Squarespace do that. If you do them separately, you will have to set up an alias redirection from your domain name to your web hosting provider, but there are more benefits having them separated compared to the convenience of buying them packaged together.

#### ☑️  Think of a good name that you want for your website
NOTE: The .com, .net, country codes, etc all cost money ($$). You’ll have to see if the name you want is available and if you have the budget for it.

#### ☑️  Pay registration for domain 💸
Pick a plan that’s within your budget and convenient BUT NOTE that if you pick the year plan (because it’s the cheapest) that you’ll have to do the domain registration process all over again next year.

#### ☑️  Redirection of DNS (Domain Name System)
Honestly, this part is usually the hardest/tedious part of creating a website because this set-up depends on both the domain registration service and your web hosting provider. If you already bought a domain, search to see which web hosting provider it’s associated with because that process will be the least painful. And vice versa.

#### ⚠ Caveats
* Pricing: These leasings usually are for a year, five years, or ten years. Again, it’ll cost money, but think if you’ll want to go through this process again next year. Or risk losing the domain name.
* Domain transfers: Check out the transfer policy in case they charge a fee.
* Alias redirection: If you don’t use a service that does both web hosting and domain registration, you’ll need to redirect the domain so it goes to your web hosting service. You’ll need to have a web hosting service set up already in order to do this.
* Where can I buy a domain name?
  * Namecheap
  * Gandi.net
  * Bluehost (example of a Wordpress provider)
  * Don’t use GoDaddy

### 🎨 Website Design
Creating the files and data: This is the fun part! If you are using website builders, they usually have templates that you can choose from. If you are building a website from scratch, then you’ll need the basics: HTML and CSS. And JavaScript if you want, but it’s not necessary.

![Alt Text](./gifs/quora-html-css-hs.gif)

#### ☑️ HTML: HyperText Markup Language
HTML Doctype: Currently, the web is on [HTML5](https://www.w3.org/TR/html52/)
###### Check out the HTML TEMPLATE

|  Code  | Term & Link | Description |
| -------------- | ---------------------------- | -------------------- |
| `<!doctype html>` | [DocType](https://www.w3schools.com/tags/tag_doctype.asp) | The Document Type Declaration (or DOCTYPE) is a document that tells the browser, “Hey! I’m a webpage! Read me!” |
<`html`> | Opening HTML tags | This begins the HTML information. |
`<html lang="en">` | [Language attribute](https://www.w3schools.com/tags/att_lang.asp) | Determines the language for the doc |
`<head>  ` | [Opening head element]() | The container holds metadata of the website: title, character set, styles, language, etc. This info is more for the browser than the user. It then needs a closing head element. |
`<meta charset="utf-8">`| [Character set]()| To display the HTML correctly, it needs to know the encoding.|
`<title> [Name of Site] </title>` | [Title Tag]()|This defines the title of the HTML document. You usually see this in the tab of the browser.|
`<style></style>` | [Style Element]() |A type of in-line CSS done in the head section.|
`</head>`| Closing head element| This closes the head element!|
`<body>` | [Opening Body Element]() | This is where the magic is down and gets shown. This is what the user sees. You put text and code in here. |
`</body>`| Closing Body Element | This closes the body element! |
`</html>`| Closing HTML tag | This closes the HTML doc! The web will know that the information stops. |



#### ☑️ CSS: Cascading StyleSheets
###### Check out the CSS TEMPLATE
* There are a bunch of templates on-line. W3 has some CSS templates that you can copy, for example. Or codepen.io!
* If you want to do something from scratch, you’ll need to research the tags and attributes. Here are some terms that might help with your search:
  * For Layout: Grid and Flexbox
  * For Colors: CSS Color Name, Hex Code, Decimal Code
  * For Fonts: Font Family, San Serif and Serif
  * Element Selectors: You can “grab” and customize div tags, class names, and id tags
  * CSS Properties: The tags and terms CSS uses on the web

# Resources

##### Blewer, Ashley. “Information Technologies“. Pratt Institute. Spring 2020.   https://github.com/ablwr/info654sp20/tree/master/syllabus
* Mozilla web docs: Introduction to HTM
* HTML Beginner Tutorial
* CSS Basics
* Current. Mozilla. Introduction to CSS
* Current. Mozilla. CSS Selectors
* CSS Beginner Tutorial

###### Codecademy. “How to Create a Website.” https://www.codecademy.com/articles/f1-create-website

###### Codecademy. “How to make a website.” Code-Along. https://www.codecademy.com/learn/make-a-website

###### Codecademy. “Learn HTML.” Code-Along.
https://www.codecademy.com/learn/learn-html

###### Josep. “How to Set up a Website in 2020: An Updated Beginner’s Guide.” 2019 Apr 4. https://www.websitetooltester.com/en/how-to-set-up-my-own-website/

###### Low, Jerry. “Beginner Guide: What is Web Hosting? What is a Domain? Difference Between a Domain Name and Web Hosting”. 2020 March 27. https://www.webhostingsecretrevealed.net/blog/web-hosting-guides/what-is-the-difference-between-a-domain-and-web-hosting/

###### WPBeginner. “WordPress.com vs WordPress.org”. Beginner’s Guide for Wordpress. 2020 Feb 4. https://www.wpbeginner.com/beginners-guide/self-hosted-wordpress-org-vs-free-wordpress-com-infograph/
