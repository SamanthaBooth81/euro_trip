h1 align="center">Clay & Fire Jewellery</h1>

<img src="assets/readme_images/responsive.png">

### **Live Site**
[Clay & Fire Jewellery Live Site](https://clay-and-fire.herokuapp.com/)

### **Repository:**
[Clay & Fire Jewellery Repository](https://github.com/SamanthaBooth81/clay_and_fire)

# About
This is a full-stack e-commerce project built using Django, Python, HTML, CSS, and JavaScript. I have created this website for 'Clay and Fire Jewellery', a business that creates handmade pieces of jewellery primarily using Polymer Clay, a lightweight and highly versatile material that is baked to cure it.

# Table of Contents

[User Experience](#user-experience)

- [Strategy](#strategy)

- [User Stories](#user-stories)

- [Scope](#scope)

- [Wireframes](#wireframes)

[Marketing Strategies](#marketing-strategies)

[Features](#features)

[Features to be Implemented](#features-to-be-implemented)

[Technologies Used](#technologies-used)

[Testing](#testing)

[Validator Testing](#validator-testing)

[Responsive Testing](#responsive-testing)

[Bugs Found](#bugs-found)

[User Feedback](#user-feedback)

[Search Engine Optimisation (SEO)](#search-engine-optimisation-seo)

[Deployment](#deployment)

[Credit](#credit)

[Acknowledgments](#Acknowledgments)

# User Experience

# Strategy

This website is for a Business to Consumer (B2C) business that sells handmade polymer clay jewellery. The target market for these products are:

- Women who enjoy fashion and accessorising.
- Those looking for gifts for people who enjoy wearing jewellery.
- Women aged between 15 and 45.

Keeping the above in mind, I believe the Customers will need a website that is:

- Easy to Navigate and filter/search by category.

- Has the ability to view and purchase items.

- Has an email subscription service.

- Has links to Social Media sites Facebook and Instagram.

- User Account functionality, to keep track of order history and store delivery information.

And the Owner will need a website that:

- Appealingly displays their products.

- Allows them to add, edit and remove products. Stock Quantities wasn't a requirement as products are handmade to order and therefore only become unavailable when the seller wishes to stop selling the product.

- Allows customers to get in contact if required whilst having some information readily available to reduce the number of contact forms received.

- Allows user to share feedback on products in order to improve products/service.

# User Stories

# Scope

To achieve the above user and business goals, this project will be created with the following features:

- Site Navigation containing a Search Bar, My Account Links, Shopping Bag links, and Product Categories sections.

- A Landing Page that clearly demonstrates what the site is for.

- A Products Page that lists the Products contained within the category/search carried out.

- Products Cards that gives the user an image of the product along with name, price, and ability to click into it for more details.

- Registration/login functionality using Django AllAuth so that users can create and manage their account.

- A User Profile Page so that users can save delivery details for faster orders in future and to see their order history.

- Custom 404 Error Page
# Structure

This project is structured with a homepage that greets the user with a clear navigation bar at the top of the page to search for the item required or to browse all products. There is the ability to sort items by price, alphabetically, and by category as well as the ability to search for a product by typing keywords into the search bar.

Furthermore, users have the option to checkout as a guest or create a profile for themselves which can contain their delivery address and does contain their order history.

## Wireframes

All wireframes were created using [Balsamiq](https://balsamiq.com/).

Clay & Fire Jewellery Wireframes for Mobile, Tablet and Desktop devices can be viewed [here](assets/documents/wireframes.pdf). I didn't add wireframes for the favourites page as it was based on the same template at the products page. 

# Marketing Strategies

The following questions were asked and answered when trying to decide on the best marketing strategy. 

1.	Which online platforms would you find lots of your users?

- Facebook
- Instagram
- Tiktok
- Etsy

2.	Would your users use social media? If yes, which platforms do you think you would find them on?

- Facebook
- Instagram
- Tiktok

3.	What do your users need? Could you meet that need with useful content? If yes, how could you best deliver that content to them?

- Style Inspiration: 
    - Instagram Posts of our jewellery styled and possible combinations
    - TikTok Videos following current editing trends
- Gift Inspiration
    - Instagram Posts of gift ideas and product combinations
    - Emails with gift ideas, particularly around Christmas or other holidays

4.	Would your business run sales or offer discounts? How do you think your users would most like to hear about these offers?

- Email deals for subscribers
- Sale Emails and Instagram Posts/Stories

5.	What are the goals of your business? Which marketing strategies would offer the best ways to meet those goals?

- Make Sales
- Gather repeat customers

6.	Would your business have a budget to spend on advertising? Or would it need to work with free or low-cost options to market itself?

- Free/low-cost marketing as the budget would need to go towards materials required to create and deliver high-quality products

I also looked at the below business as they both also sell polymer clay jewellery. As you can see from both of these examples their most successful Social Media platform in terms of following is TikTok, followed by Instagram, and lastly Facebook. 

### Shopmalcreates: 
FB Page 535 likes, Instagram 32.7k followers, TikTok 1232 followers

### Indigo Sands: 
FB Page 4037 likes, Instagram 92.4K followers, TikTok 225.7K followers

Although seemingly a successful tool for building a following, as TikTok is a fast-paced video based platform, I have created Instagram and Facebook accounts to act as the Social Media platforms this business uses alongside email marketing. 

### Facebook

<img src="assets/readme_images/fb-page1.png">

<img src="assets/readme_images/fb-page2.png">

### Instagram

### Subscription

Users are also able to subscribe to receive the Clay & Fire Jewellery Newsletter via the Mailchimp form found in the footer. Subscription email would contain Upcoming Sale information and current deals. 

<img src="assets/readme_images/subscribe.png" height="250px">

# Features

## Homepage

### Logo / Shop Name

<img src="" width="50%">

### Site Navigation

<img src="" width="100%">

## 404 Error Page

<img src="" width="50%">

## Colour Scheme 

The colour scheme for the project was put together using [Adobe Color](https://color.adobe.com/create/image) by uploading the landing page image. The colour scheme decided is:

<img src="assets/readme_images/colour-theme.png" width="500px">

## Font Choice

I chose the Google Font [Caveat](https://fonts.google.com/specimen/Caveat?preview.text=The%20London%20Escapists&preview.text_type=custom) to act as the Logo font for the website.

For the remainder of the website I chose the Google Font [Quicksand](https://fonts.google.com/specimen/Quicksand?preview.text=The%20London%20Escapists&preview.text_type=custom).

## Favicon 
I created a basic Favicon for this project using [Canva](https://www.canva.com/). 

<img src="assets/readme_images/favicon.png" height="150px"> 

# Features to be Implemented
The following features can be implemented to enhance the project:

- 

# Technologies Used
## Languages Used

[html](https://en.wikipedia.org/wiki/HTML)

[CSS](https://en.wikipedia.org/wiki/CSS)

[JavaScript](https://www.javascript.com/)

## Frameworks, Libraries, and Programmes Used 

[GitHub](https://github.com/) - Holds the repository of my project, GitHub connects to GitPod and Heroku.

[GitPod](https://gitpod.io/workspaces) – Connected to GitHub, GitPod hosted the coding space, allowing the project to be built and then committed to the GitHub repository. 

[Bootstrap](https://getbootstrap.com/) - Used to quickly add design and responsiveness to my website, Bootstrap focuses on mobile first design meaning this website is responsive across multiple devices and screen sizes.

[Font Awesome](https://fontawesome.com/) - Used for all of the icons throughout the site.

[Canva](https://www.canva.com/) - Used to create the favicon for the project.

[Image Compressor](https://imagecompressor.com/) - Used to compress the website and product images.

# Testing
## **Manual Testing by User Story**

# Validator Testing

- The HTML templates were validated using [W3 Validator](https://validator.w3.org/nu/#textarea). No major errors were returned for the HTML segments.
- The CSS style sheet was validated using [W3C Validator](https://jigsaw.w3.org/css-validator/#validate_by_input) and no errors were returned.
- The JavaScript files were run through [JSHint](https://jshint.com/) and no errors were found apart from a few missing semi-colons which were added. Also, the project was run through whilst checking for any issues in the console. No errors were found.
- The code was validated using [PEP8](http://pep8online.com/). No errors were returned.
- The finished project was also run through [Wave](https://wave.webaim.org/) to check for issues with contrast styling and HTML structure. 

# Responsive Testing

I also tested this project's responsiveness across multiple devices including:

- iPhone X
- iPhone 8
- Samsung S21 FE
- Samsung S10+
- Samsung Galaxy Z Flip3
- iPad Pro 9.7"
- MacBook Pro 13"

I also used Google developer tools to check responsiveness across multiple other devices and screen sizes. 

# Bugs Found 

- 

# User Feedback 

- 

# Search Engine Optimisation (SEO)
To find the relevant keywords for my project I made the following searches on [Google](www.google.co.uk) and [Word Tracker](www.wordtracker.com)  along with a few combinations:

- 

Of the above, the top combination of searches I found were:

- 

Of the above searches, REPLACE THIS WITH BEST OPTION best suited what my project is selling and had the highest search rate of all keywords attempted. With that in mind, I have selected the following to be included in my projects metadata:

- 

# Deployment 

# Credit
## Content 

### Styling

### Website Images

- 

The images used in this project were also compressed using (OptimiZilla)[https://imagecompressor.com/].

- [Favicon Generator](https://favicon.io/favicon-converter/) used to generate a favicon image from a jpg image.

# Acknowledgments