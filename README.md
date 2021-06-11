# tie-ups UK 
https://belt26.github.io/tie-ups-uk/

## Author: Helen Taylor  
## Version 1.0.0

![Site preview on a variety of devices](https://github.com/BelT26/tie-ups-uk/blob/master/assets/images/responsive-preview-tie-ups.PNG)



## Motivation  
After being furloughed during the pandemic, a friend of mine has begun importing and selling eco-friendly belts produced by her brother's company in Italy: [tie-ups Italian site](https://www.tie-ups.it/?v=1471e3d26b3e)  

As the company site is in Italian only and includes merchandise not stocked by my friend, to help her promote the products I offered to create a  different website for her for the UK market that focused on her key ranges of accessories. The site is intended to introduce the brand to potential UK customers, showcase the main products she is promoting, provide contact details and the opportunity so sign up to a mailing list.

## Branding  
I retained the white text on a blackground of the original site header for maximum contrast.  I created a new logo using the MuseoModerno font from Google Fonts and the ribbon icon from Font Awesome.  

To indicate the active page and clickable links throughout the site I used the color 'darkgoldenrod' which complements the main image on the homepage and reflects the idea of a luxury range.  

## Features  

### Navigation Bar  
This allows users to navigate easily to each page on the site without having to use the back button.  

Media queries were added to center the links on mobile devices and to move the logo to a separate line to prevent overlapping.   

## Main Image 
![Landing page main image of studded belt](https://github.com/BelT26/tie-ups-uk/blob/master/assets/images/home-page-main-img.PNG) 
I wanted to maximize the visual impact on the user by featuring a striking images of one of the range of belts. I tried creating a hero image which took up 100% of the width but preferred the effect with whitespace either side. 

The brand logo, which is the main heading of the page, was positioned over the photograph as an h1 element.

## About Section 
![Snakeskin effect belt draped over leaves and text describing company ethos](https://github.com/BelT26/tie-ups-uk/blob/master/assets/images/about-img-description.PNG) 
This section informs the user of the company's sustainable, animal-friendly values and the USPs of the products.  

I selected a photograph that both reflected the company ethos by depicting a belt against a backdrop of leaves and provided a flattering image of one of the main products. 


## Footer  
The footer contains links that allow the user to connect to the company Facebook and Instagram pages.  

To prevent overlapping on smaller devices I added a media query change the display of the company logo to 'none' so that only the clickable social media links are visible.  

The links currently take the user to the Facebook and Instagram home pages. These will be amended to link directly to my friend's social media accounts in the future.  


## Products Page  
![First section on product page containing 3 snakeskin effect belts](https://github.com/BelT26/tie-ups-uk/blob/master/assets/images/products-page.PNG)

This page displays images of the main products in the current collection.  

Underneath the header two links have been added that take the user either to the map section of the contacts page or the contact form.  

On mobile devices the ranges of belts are listed before the whole selection of products to allow the user to navigate more easily to the style of belt they are interested in.

A zoom feature was added to offer the user a closer view of the product. The initial effect did not look very smooth and so I added CSS transition properties to improve the viewing experience.   

Currently 18 products are listed. More will be added as my friend's stock expands.  


## Contacts Page  

### Form  
![Image of sign up form](https://github.com/BelT26/tie-ups-uk/blob/master/assets/images/form.PNG)
The form would eventually allow the user to subscribe for special offers on the product.  
The form contains a text area that allows the user to include any queries or requests.  

### Map and Contact Details  
![Image of map showing store location and contact details](https://github.com/BelT26/tie-ups-uk/blob/master/assets/images/store-location.PNG)
This section directs the user to Wratten's Gift Shop in Chislehurst from which my friend sells the belts.  
To the right of the map the user is provided with contact details and opening hours.  


## 404 Page
![Image of page user lands on if incorrectly typing a page address, with links to return to the site](https://github.com/BelT26/tie-ups-uk/blob/master/assets/images/404-page.PNG)
This page appears if the user incorrectly types one of the page addresses and provides them with links back to the site without them having to use the back button. 


## Responsive elements  

### Header  
The elements in the header are centered and the navigation bar appears below the logo on smaller devices.

### Main Image
A rotated image is used for smaller screens and the cover text is removed.

### About Section  
The image stacks above the text on smaller screens. 

A slimmer portrait image replaces the original on mobile devices.

### Footer  
The logo is hidden and the social media links are indented on small screens.  

### Products page  
The layout of the items in each range changes from 3 x 2 to 2 x 3 or 1 x 6 according to the screen size. 

### Map  
The map stacks above the contact details on smaller screens.  


## Testing  

### Validator testing  

*HTML
No errors were returned when passing through the official [W3C validator: tie-ups/about](https://validator.w3.org/nu/?doc=https%3A%2F%2Fbelt26.github.io%2Ftie-ups-uk%2F) [tie-ups/products](https://validator.w3.org/nu/?doc=https%3A%2F%2Fbelt26.github.io%2Ftie-ups-uk%2Fproducts.html)[tie-ups/contacts](https://validator.w3.org/nu/?doc=https%3A%2F%2Fbelt26.github.io%2Ftie-ups-uk%2Fcontacts.html).

*CSS
No errors were returned when passing through the official [Jigsaw validator: tie-ups](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fbelt26.github.io%2Ftie-ups-uk%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en).

The contrast between the font colour of the active page title and the links in the header and footer was checked on the WebAim contrast checker and scored 6.45 [WebAim contrast checker - dark golden rod / black](https://webaim.org/resources/contrastchecker/)


### Challenges  
I originally intended to use media queries to amend the number of products displayed horizontally from 3 to 2 to 1 according to the device width.  As I was struggling with items overlapping and finding the right breakpoints, I decided to research slack for some other suggestions and found the following post very helpful [Igor CSS Grid Post on Slack](https://code-institute-room.slack.com/archives/C0L316Z96/p1620317611161800). This also led me on to the following flexbox tutorial on youtube[webdev Simplified Flexbox Tutorial](https://www.youtube.com/watch?v=fYq5PXgSsbE).

Through Flexbox I managed to resize the images responsively and I applied the same technique to stack images on top of text on smaller screens for the home page and the contacts page.  I found the following documentation very helpful to refer to [Mdn Flexbox Documentation](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox).

User feedback indicated that on mobile devices the list appeared quite lengthy to scroll through and so for smaller screens I added a section at the top of the page to enable the user to navigate directly to the range they are interested in. I also included a button after each section that the user could click on to return to the top of the page.  This feature is currently hidden on larger devices due to the number of products currently offered but it could be enabled as the collection expands.

The original images used did not resize well for mobile devices so I instead of using HTML image tags I added them as background images in my css file that would be replaced with portrait style images through media queries on smaller screens. I used the following site for advice on how to add the description [David MacD blog](https://www.davidmacd.com/blog/alternate-text-for-css-background-images.html)


I had difficulty linking the 404.html page to my site and after several hours unsuccessfully googling solutions my mentor assisted me by advising me to create the 404.md file.


## Deployment  
The site was deployed to GitHub pages following the steps below: 

* From the project repositoy I navigated to the Settings tab.  
* I selected the Master Branch from the source section drop-down menu.  
* The page refreshed automatically with a message confirming successful deployment.  
* The live link can be found here https://belt26.github.io/tie-ups-uk/  


## Credits  

### Content  
Text content on the home page was based on content translated and condensed from the Italian tie-ups web site [tie-ups Italy company info](https://www.tie-ups.it/mondo-tie-ups/?v=1471e3d26b3e).  

### Media
* The two images on the home page were taken by a professional photographer, Tony Cullinane [Tony Cullinane Photography - Facebook Page](https://www.facebook.com/TonyCullinanePhotography) 
* All product images were provided by the Italian tie-ups company.
* The map image was taken from Google Maps.
* The icons for the logo and social media links were taken from Font Awesome
* The fonts used were imported from Google Fonts.
* The image on the custom 404 page was by Christelle Olivier and downloaded from [Pixabay]("https://pixabay.com/vectors/404-error-error-404-panel-3060993/").  

## Future Development Possibilities

* Back end development that links the form to a client database  
* Update link to social media accounts  
* Add a shopping cart feature and the possibility of purchasing items online  
* Expand range of products featured  




