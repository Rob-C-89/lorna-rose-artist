
# Lorna Rose - Artist

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/screenshots/techsini-mockup.png)

## Description:

The Lorna Rose - Artist website is a website for a professional artist Lorna Rose

The business goals of the website are to make the artist’s art available to view online, securing commissions (art sales, commissioned portraits and art lessons), and providing a contact form for users. 

The target audience is fans of the artist's work, or those who might be curious about it and want to see more.

The site will be useful to users looking to purchase an art piece, commission a portrait or book a lesson. 


## User Experience:

The website has a simple layout typical of many websites, which most users would be familiar with. The user should find it easy to navigate the website, find the information they require, and perform the action of contacting the owner.

### Colour Scheme

The colour scheme was devised by taking colours from the header image and lead image (Short Haired Man), and utilising them to give a coherent color scheme to the page with a defined contrast.

### Contrast

Colour scheme was checked for contrast using www.colourcontrastchecker.com. The navbar and footer conform to WCAG AA standards, with the rest of the site conforming to AAA standards. I wouldn't have accepted the main body of the site reaching AA, but found AA standards for the navbar and footer to be acceptable.

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/screenshots/contrast-1.png)

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/screenshots/contrast-2.png)

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/screenshots/contrast-3.png)


## Typography

Google Fonts was used for the typography. The cursive header font was used, as the style felt coherent with the subject of the website. A sans-serif font was used for body paragraph text for ease of reading.

### User Stories

The user stories have been outlined in the projects folder of the repository. They can be found here:

[User Stories](https://github.com/users/Rob-C-89/projects/4)


## Features:


### Navigation bar

The navbar is displayed at the top of the website, on all three pages. It displays the name of the website and includes links to the About, Commissions and Tuition sections on the homepage, the Gallery page, and the Contact page. Remaining identical on all pages, the user should be able to navigate the website with ease.

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/screenshots/homepage-1.png)


 The navigation bar is fully responsive, and collapses on smaller devices.

 ![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/screenshots/nav-bar-collapsed.png)


### Header Image 

The header image is displayed across all pages on the website, with overlaid text displaying the name of the artist and her speciality. This ties the website together, and makes clear to the user the purpose of the website.

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/screenshots/header.png)


### Homepage

The homepage contains three sections, each with an image by the artist. This communicates information to the user about the artist and the services they provide.


![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/screenshots/homepage-1.png)


![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/screenshots/homepage-2.png)

### Footer

A footer is displayed across all pages of the site, with copyright information and links to social media accounts, which open in a new browser tab.

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/screenshots/footer.png)

Please note the artist's accounts are incomplete/unavailable, so the links currently open to the homepage of the relevant sites. These would be updated or removed as necessary.


### Gallery

The gallery page displays six of the artist’s paintings and information on their price and medium. This section would be updated with new works as they become available, and works that have been sold would be removed.

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/screenshots/gallery-tablet.png)


This section is valuable to the business as one of the key goals of the site is to provide online sales of the artist’s work. It is valuable to users who want to purchase art, or simply to view it as an enthusiast.



### Contact

The contact page contains a form for the user, with a dropdown selection containing the three main services the artist provides. The form will not send if the user's contact information is incomplete.

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/screenshots/contact-form.png)


### Successful submission page

Upon completing the form successfully, the user is taken to a page telling them the form has been sent and the site owner will reply shortly. This is to assure the user that their action has been successful and boost confidence in the site’s efficacy. A button below the message will return the user to the homepage.

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/screenshots/success.png)


### Custom 404 page

I have created a custom 404 error page which is displayed when a broken link is followed

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/screenshots/custom-404.png)

## Testing

### Manual Testing

The website has been tested as a user and all features work as intended.

The website has been tested for responsivity using Chrome DevTools. The navbar links collapse into a burger icon on smaller screens. 

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/screenshots/nav-bar-collapsed.png)


On smaller screens, the homepage text and images rearrange into a single column, with a CSS media query to reorder the image and text (from text, image, image, text, text, image, to alternating text and image).

The gallery images are displayed in two rows of three on large devices, three rows of two on medium devices, and a single column of six on small devices. It felt important to preserve the size of the images rather than reduce them with the size of the screen, given the importance of the images to both the business and user.

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/screenshots/gallery-large.png)

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/screenshots/gallery-laptop.png)

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/screenshots/gallery-tablet.png)

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/screenshots/gallery-mobile.png)


The images are set to height 300px to ensure they are displayed in full on smaller devices, with the gallery images increasing to 400px on larger screens for more impact. I was initially using a percentage height rule for images, which led to stretching on medium screens. After debugging, I came to realise a fixed height was more appropriate (as on mobile devices, the images wouldn’t fit on the screen, not a good feature for an image-driven site).


### Form Testing

The form has been tested, so that it won't send unless all inputs are filled in correctly:

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/screenshots/form-required-name.png)

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/screenshots/form-required-input-type.png)

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/screenshots/form-require-select.png)


Styling the burger icon on the Bootstrap navbar took some online research, with some lines of code taken directly from Stack Overflow to prevent an unattractive highlighting of the icon when active.

### Validator Testing

All of the site's pages have been passed through the w3c HTML and CSS validator. No errors are displayed.

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/validation/validator-homepage.png)

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/validation/validator-gallery.png)

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/validation/validator-contact.png)

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/validation/validator-success.png)

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/validation/validator-404.png)

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/validation/validator-CSS.png)

### Lighthouse

All of the site's pages have been testing using Chrome Lighthouse for performance, accessibility and best practice. The scores were acceptable and displayed below: 

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/lighthouse/lighthouse-home-desktop.png)

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/lighthouse/lighthouse-home-mobile.png)

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/lighthouse/lighthouse-gallery-desktop.png)

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/lighthouse/lighthouse-gallery-mobile.png)

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/lighthouse/lighthouse-contact-desktop.png)

![screenshot](https://github.com/Rob-C-89/lorna-rose-artist/blob/main/documentation/lighthouse/lighthouse-contact-mobile.png)





## Unfixed Bugs

There are no known unfixed bugs to the developer.

## Deployment

The site was deployed to GitHub pages using the following steps (sourced from Code Insitute Full Stack Diploma):

1. In the GitHub repo., navigate to Settings
2. On the left-hand sidebar, in the Code and automation section, select Pages.
3. Make sure:
    * Source is set to 'Deploy from Branch'.
    * Main branch is selected.
    * Folder is set to / (root).
4. Under Branch, click Save.


The link to view the site is as follows: https://rob-c-89.github.io/lorna-rose-artist/

### Cloning

Cloning a repository pulls down a full copy of all the repository data that GitHub.com has at that point in time, including all versions of every file and folder for the project. You can push your changes to the remote repository on GitHub.com, or pull other people's changes from GitHub.com. 

You can clone the repository from using the following steps:

1. On GitHub, navigate to the main page of the repository
2. Above the list of files, click  <> Code.
3. Select whether you prefer HTTPS, SSH or CLI, then copy the URL with the clipboard icon
4. Open Git Bash or Terminal
5. Change the current working directory to the location where you want the cloned directory.
6. Type git clone, and then paste the URL. It will look like this:
    * git clone https://github.com/Rob-C-89/lorna-rose-artist
7. Press Enter to create your local clone.


### Forking 

As an alternative to cloning the repo, you may fork it to your account. This will keep your version free from source updates, allowing you to work on the repository without code or content being altered.

You can fork the repository using the following stepsL

1. Log into your account then navigate to the repository:
    * https://github.com/Rob-C-89/lorna-rose-artist
2. In the top-right corner of the window, you'll see a "Fork" button. 
3. Click the Fork button to begin the forking process.


## Credits:

### Content:

JSS Code to collapse the bootstrap navbar icon on smaller devices when navigating to internal links was taken from Code Institute’s Full Stack Software course.

Code to prevent the navbar icon from highlighting when active was taken from Stack Overflow

Bootstrap templates were used for the navbar, contact form and cards on the gallery page.

Code was formatted using Prettier Code Formatter


### Media:

The website’s copyright-free header image was taken from stock photos website https://www.pexels.com/

Portrait images on homepage and gallery were provided by Lorna Rose with her permission

Google Fonts was used for custom fonts

Font Awesome was used for social media icons in the footer and site favicon

Techsini Mockup was used for the website mock-up image at the beginning of the read me file

Images sizes were reduced using www.tinyjpeg.com

Images were converted to webp using www.convertio.co




