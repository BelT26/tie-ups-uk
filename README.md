# tie-ups UK 


## Author: Helen Taylor  
## Version 1.0.0

## Motivation  
After being furloughed during the pandemic, a friend of mine has begun importing and selling eco-friendly belts produced by her brother's company in Italy:    
[tie-ups Italian site](https://www.tie-ups.it/?v=1471e3d26b3e)
As the company site is in Italian only and includes merchandise not stocked by my friend, to help her promote the products I offered to create a  different website for her for the UK market that focused on her key ranges of accessories. The site is intended to introduce the brand to potential Uk customers, showcase the main products she is promoting, provide contact details and the opportunity so sign up to a mailing list.

## Branding  
I retained the white text on a blackground of the original site header for maximum contrast.  I created a new logo using the MuseoModerno font from Google Fonts and the ribbon icon from Font Awesome.  
To indicate the active page and clickable links throughout the site I used the color 'darkgoldenrod' which complements the main image on the homepage and reflects the idea of a luxury range.  

## Features  

### Navigation Bar  
This allows users to navigate easily to each page on the site without having to use the back button.  
Media queries were added to center the links on mobile devices and to move the logo to a separate line to prevent overlapping.   

## Main Image 
![Landing page main image of studded belt]("https://github.com/BelT26/tie-ups-uk/blob/master/assets/images/TieUp%20Belts-12.jpg") 
I wanted to maximize the visual impact on the user by featuring a striking images of one of the range of belts.  
The brand logo, which is the main heading of the page, was positioned over the photograph as an h1 element.

## About Section 
![Snakeskin effect belt draped over leaves]("https://github.com/BelT26/tie-ups-uk/blob/master/assets/images/Snake%20Belt%20cropped.jpg") 
This section informs the user of the company's sustainable, animal-friendly values and the USPs of the products.  
I selected a photograph that both reflected the company ethos by depicting a belt against a backdrop of leaves and provided a flattering image of one of the main products. 


## Footer  
The footer contains links that allow the user to connect to the company Facebook and Instagram pages.  
To prevent overlapping on smaller devices I added a media query change the display of the company logo to 'none' so that only the clickable social media links are visible.  
The links currently take the user to the Facebook and Instagram home pages. These will be amended to link directly to my friend's social media accounts in the future.  

## Products Page  
![Sample product image - Navy Scribble Belt]("https://github.com/BelT26/tie-ups-uk/blob/master/assets/images/B-C413%20SCHIZZO%20BLU-WHITE%20fb.jpg")
This page displays images of the main products in the current collection.  
Underneath the header two links have been added that take the user either to the map section of the contacts page or the contact form.  
A zoom feature was added to offer the user a closer view of the product. The initial effect did not look very smooth and so I added CSS transition properties to improve the viewing experience.   
Currently 18 products are listed. More will be added as my friend's stock expands.  


## Contacts Page  

### Form  
The form allows the user to subscribe for special offers on the product.  
The form contains a text area that allows the user to include any queries or requests.  

### Map and contact details  
This section directs the user to Wratten's Gift Shop in Chislehurst from which my friend sells the belts.  
To the right of the map the user is provided with contact details and opening hours.  

## Responsive elements  

### Header  
The elements in the header are centered and the navigation bar appears above the logo on smaller devices.


### About section  
The image stacks above the text on smaller screens  

### Footer  
The logo is hidden and the social media links are centered on small screens.  

### Products page  
The layout of the items in each range changes from 3 x 2 to 2 x 3 or 1 x 6 according to the screen size. 

### Map  
The map stacks above the contact details on smaller screens.  


## Testing  

### Validator testing  

### Challenges  
I originally intended to use media queries to amend the number of products displayed horizontally from 3 to 2 to 1 according to the device width.  As I was struggling with items overlapping and finding the right breakpoints, I decided to research slack for some other suggestions and found the following post very helpful [Igor CSS Grid Post on Slack](https://code-institute-room.slack.com/archives/C0L316Z96/p1620317611161800). This also led me on to the following flexbox tutorial on youtube[webdev Simplified Flexbox Tutorial](https://www.youtube.com/watch?v=fYq5PXgSsbE).
Through Flexbox I managed to resize the images responsively and I applied the same technique to stack images on top of text on smaller screens for the home page and the contacts page.  I found the following documentation very helpful to refer to [Mdn Flexbox Documentation](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox).


## Deployment  
The site was deployed to GitHub pages following the steps below.  
From the project repositoy I navigated to the Settings tab.  
I selected the Master Branch from the source section drop-down menu.  
The page refreshed automatically with a message confirming successful deployment.  
The live link can be found here https://belt26.github.io/tie-ups-uk/  


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
Back end development that links the form to a client database  
Update link to social media accounts  
Possibility of purchasing items online  
Expand range of products featured  




