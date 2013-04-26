---
title: 'Project: Alt Foundry'
layout: post
design_type: 'Website Design and Development'
case_study_link: 'http://alt-foundry.com'
designs: '
<div class="cover_image">
  <img src="data:image/svg+xml;" alt="alt foundry logo"/>
</div>

<div class="image_container">
  <noscript data-alt="alt-foundry homepage" data-src="http://sicanstudios.com/images/work/alt-foundry/homepage.jpg" data-src-retina="http://sicanstudios.com/images/work/alt-foundry/homepage@2x.jpg"><img src="http://sicanstudios.com/images/work/alt-foundry/homepage.jpg" alt="alt-foundry homepage"></noscript>
</div>

<div class="image_container">
  <noscript data-alt="alt-foundry font page" data-src="http://sicanstudios.com/images/work/alt-foundry/font-page.png" data-src-retina="http://sicanstudios.com/images/work/alt-foundry/font-page@2x.png"><img src="http://sicanstudios.com/images/work/alt-foundry/font-page.png" alt="alt-foundry font page"></noscript>
</div>

<div class="image_container">
  <noscript data-alt="alt-foundry about" data-src="http://sicanstudios.com/images/work/alt-foundry/about.png" data-src-retina="http://sicanstudios.com/images/work/alt-foundry/about@2x.png"><img src="http://sicanstudios.com/images/work/alt-foundry/about.png" alt="alt-foundry about"></noscript>
</div>

<div class="image_container">
  <noscript data-alt="alt-foundry type-tester" data-src="http://sicanstudios.com/images/work/alt-foundry/type-tester.png" data-src-retina="http://sicanstudios.com/images/work/alt-foundry/type-tester@2x.png"><img src="http://sicanstudios.com/images/work/alt-foundry/type-tester.png" alt="alt-foundry type-tester"></noscript>
</div>

<div class="image_container">
  <noscript data-alt="alt-foundry footer" data-src="http://sicanstudios.com/images/work/alt-foundry/footer.png" data-src-retina="http://sicanstudios.com/images/work/alt-foundry/footer@2x.png"><img src="http://sicanstudios.com/images/work/alt-foundry/footer.png" alt="alt-foundry footer"></noscript>
</div>
'
---

Alt-Foundry is a company that sells fonts. I was hired to designed and develop a complete e-commerce solution that would act as a platform for selling and promoting their fonts.
<!--more-->

##What I learned
I got a ton of back-end (PHP) experience from this project. I learned how challenging it is to create an e-commerce platform on top of WordPress. I also learned how to create images with PHP on the fly (implemented when live-testing each font). I also learned and applied online shopping cart best practices (one-click checkout, etc.).


##Concept Idea
The client requested from me to design and develop a complete e-commerce website for selling fonts. With my previous experience in creating e-commerce websites, I confidently accepted the project.

For the design of the website, he gave me complete creative freedom, asking only the website to have a simple, minimalistic design. Having shown him the first drafts, he was very happy with the initial result.

<a href="http://sicanstudios.com/images/work/alt-foundry/homepage@2x.jpg" class="img" target="_blank"><img src="http://sicanstudios.com/images/work/alt-foundry/homepage.jpg" alt="alt foundry website" title="Alt-Foundry website" /></a>

##Functionality
The website should be able to do the following (everything was implemented):
<ul>
  <li>subscribe to the weekly newsletter</li>
  <li>display latest fonts, sort fonts by &#8220;new&#8221;, &#8220;popular&#8221;, or &#8220;free&#8221;</li>
  <li>test fonts on-site, provide JavaScript alternative previews</li>
  <li>add, edit and remove products from cart (visual feedback)</li>
  <li>search for a product</li>
  <li>change quantity within the cart</li>
  <li>easy, one step checkout</li>
  <li>send e-mail confirmation on purchase, automatically generate receipts</li>
  <li>generate link and send the digital products</li>
  <li>provide statistics of purchases</li>
  <li>ability to add periodical discount codes</li>
</ul>

##Production
The website was coded in valid xHTML Strict 1.0 and CSS3. Once all the design assets were created and a static website coded, it was then transcoded into PHP for a WordPress theme. The website was search engine optimised (SEO) in order to attract more visitors from search engines.

Browsing the Internet and researching other font selling websites like <a href="http://new.myfonts.com/" target="_blank">MyFonts</a>, I decided that online testing of the fonts prior to purchasing is crucial for the potential buyer. It shows how the font and variations of the font will look with some user inputed text. I could not rely on the browser&#8217;s font rendering engine to display the text because every browser and OS renders the fonts differently.

<img src="http://sicanstudios.com/images/work/alt-foundry/testing-fonts.jpg" alt="testing fonts" />

In order to depict an accurate representation of the font, images had to be used to show the custom text. Whenever the user typed in some text, using PHP I would have the server render a PNG image with the typed text, using that particular font, and sent back to the user. Coding this script proved to be the most challenging part of this project.

Moreover, if the font family consisted of only one font, in the fonts&#8217; testing area, the font at different sizes (144px, 72px, 48px, 36px, 30px) would be displayed. If the font family consisted of more than one font, all the other type families (for example: bold and italic) would be displayed with a &#8220;buy button&#8221; to buy the fonts individually if the user wanted.

<h2>Accessibility &amp; Security</h2>
In matters of accessibility all images were added an <code>alt</code> tag, a &#8220;skip to content&#8221; link was added at the top making it easier for blind users to browse the website. On top of that semantic coding, a sitemap of the website, commenting on code to make it easy for updating, and more.

When creating the testing of the fonts, it was necessary to add a no JavaScript alternative. Because testing the fonts was partially done using JS in case the user had JS disabled, the fallback would be to display the fonts as an image (without the possibility to test the fonts). In this way, the fonts can still be seen and bought if desired.

<img src="http://sicanstudios.com/images/work/alt-foundry/no-javascript.jpg" alt="no javascript fonts" />

In the contact form, if the completed fields were incorrect, using jQuery, the erroneous fields would have a red coloured background and the website would request from the user to correct those fields. Moreover, checking the fields again back-end was necessary, in case someone with JavaScript disabled tried to &#8220;trick&#8221; the system entering phony details.

##Devils is in the details
Great attention was given to small details. Small visual cues improving the user&#8217;s browsing experience can be seen throughout the website. For every button, link or image there is a default state, a hover state, and a click state, thus making the website responsive to the user&#8217;s actions. When clicking on an input field, like in the contact form, the field would change its colour, clearly pointing to the user which field they&#8217;re filling.

Whenever the user would add a product to the cart, a bar on top of their browser would appear saying that the product was added to the cart. Even if they would click to add the product in their cart again, the product would not be added twice.

Besides the message bar, the cart button in the header, prominent in all of the website&#8217;s pages, would display the amount of products the user has in their cart. If the user would hover the button, it would dropdown, displaying the total amount for the products. Once clicked, they would be taken to the cart page. The cart was designed with cookies, so the product would remain in the cart even after you would close the website (it would save the session until you closed the browser).

<img src="http://sicanstudios.com/images/work/alt-foundry/cart-functionality.jpg" alt="cart functionality" />

##Shopping Cart
The cart features a simple one-step checkout, no sign-up required. In the cart page, the user can remove products from the cart, add a discount code, or clear their cart. Once they are done, all they have to do is click to pay via PayPal.

If the fonts are free of charge, instead of the PayPal button, a download button is displayed. Once clicked, the fonts in the cart are downloaded as a ZIP file and the cart is cleared.

<img src="http://sicanstudios.com/images/work/alt-foundry/checkout-button.jpg" alt="checkout button" />

In conclusion this project was challenging but fun to complete. I enjoyed collaborating with Andreas and learned a lot from this project that will prove useful in the future.