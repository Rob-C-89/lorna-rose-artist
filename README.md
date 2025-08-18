INCOMPLETE


Lorna Rose - Artist

![alt text](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/homepage-1.png)

Description:

The Lorna Rose - Artist website is a website for a professional artist Lorna Rose

The business goals of the website are to make the artist’s art available to view online, securing commissions (art sales, commissioned portraits and art lessons), and providing a contact form for users. 

The target audience is fans of the artist's work, or those who might be curious about it and want to see more.

The site will be useful to users looking to purchase an art piece, commission a portrait or book a lesson. 


How to use the project:
The website has a simple layout typical of many websites, which most users would be familiar with. The user should find it easy to navigate the website, find the information they require, and perform the action of contacting the owner.


Features:

Navigation bar

The navbar is displayed at the top of the website, on all three pages. It displays the name of the website and includes links to the About, Commissions and Tuition sections on the homepage, the Gallery page, and the Contact page. Remaining identical on all pages, the user should be able to navigate the website with ease.

 The navigation bar is fully responsive, and collapses on smaller devices.

Header Image 

The header image is displayed across all pages on the website, with overlaid text displaying the name of the artist and her speciality. This ties the website together, and makes clear to the user the purpose of the website.

Homepage

The homepage contains three sections, each with an image by the artist. This communicates information to the user about the artist and the services they provide.

Footer

A footer is displayed across all pages of the site, with copyright information and links to social media accounts, which open in a new browser tab.

Please note the artist's accounts are incomplete/unavailable, so the links currently open to the homepage of the relevant sites. These would be updated or removed as necessary.


Gallery

The gallery page displays six of the artist’s paintings and information on their price and medium. This section would be updated with new works as they become available, and works that have been sold would be removed.


This section is valuable to the business as one of the key goals of the site is to provide online sales of the artist’s work. It is valuable to users who want to purchase art, or simply to view it as an enthusiast.

Contact

The contact page contains a form for the user, with a dropdown selection containing the three main services the artist provides. The form will not send if the user's contact information is incomplete.

Successful submission page

Upon completing the form successfully, the user is taken to a page telling them the form has been sent and the site owner will reply shortly. This is to assure the user that their action has been successful and boost confidence in the site’s efficacy. A button below the message will return the user to the homepage.

Testing

The website has been tested as a user and all features work as intended.

The website has been tested for responsivity using Chrome DevTools. The navbar links collapse into a burger icon on smaller screens. 

On smaller screens, the homepage text and images rearrange into a single column, with a CSS media query to reorder the image and text (from text, image, image, text, text, image, to alternating text and image).

The gallery images are displayed in two rows of three on large devices, three rows of two on medium devices, and a single column of six on small devices. It felt important to preserve the size of the images rather than reduce them with the size of the screen, given the importance of the images to both the business and user.

The images are set to height 300px to ensure they are displayed in full on smaller devices, with the gallery images increasing to 400px on larger screens for more impact. I was initially using a percentage height rule for images, which led to stretching on medium screens. After debugging, I came to realise a fixed height was more appropriate (as on mobile devices, the images wouldn’t fit on the screen, not a good feature for an image-driven site).

Styling the burger icon on the Bootstrap navbar took some online research, with some lines of code taken directly from Stack Overflow to prevent an unattractive highlighting of the icon when active.

Validator Testing

Incomplete

Unfixed Bugs

There are no known unfixed bugs to the developer.

Deployment

The site was deployed to GitHub pages.

The link to view the site is as follows: https://rob-c-89.github.io/lorna-rose-artist/


Credits:

Content:

Credit code institute’s websites?
JSS Code to collapse the bootstrap navbar icon on smaller devices when navigating to internal links was taken from Code Institute’s Full Stack Software course.
Code to prevent the navbar icon from highlighting when active was taken from Stack Overflow
Bootstrap templates were used for the navbar, contact form and cards on the gallery page.


Media:

The website’s copyright-free header image was taken from stock photos website https://www.pexels.com/
Portrait images on homepage and gallery were provided by Lorna Rose
Google Fonts was used for custom fonts
Font Awesome was used for social media icons in the footer
# lorna-rose-artist


