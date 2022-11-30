# Eoin O'Sullivan Artist Site
This website is designed to provide information on an artist, examples of work and an opportunity to get in touch directly with the artist. The site is targeted towards commisioners and other artists who could potentially be collaborators, with the biography on the homepage giving background to the work that is displayed on the gallery page. There are opportunities for visitors to the site to get in touch with the artist through a contact form and links to other sites where the artist hosts work such as Instagram and Bandcamp.

![Am I responsive Screenshot](/assets/readme_images/am_i_responsive_screenshot.png)

## Features

### Existing Features
- Navigation Bar
  - The Navigation bar is a consistent feature across all three pages of the site, allowing easy movement between all of the content.
  - It contains the site title (which also links to the home page) as well as a menu allowing users to select the Home page, Gallery page or Contact page.
  - The links are hover responsive to increase user feedback and also display which page is active to decrease chances of confusion.

![Navigation Bar](/assets/readme_images/header.png)

- Landing Page Image
  - The Image that greets the site visitor is a snippet of a photograph that is contained in the gallery. Only a section of the image is shown to try and invite user to find out more.

![Landing Page Image](/assets/readme_images/cover_image.png)

- Biography Paragraph & Teaser Images
  - The content on the homepage consists of paragraphs of information about the artist split up with teaser images.
  - The bio paragraphs are intended to teach the visitor about the artist and their background. It also serves as an outline of the site purpose and what the visitor can expect.
  - Teaser images are inserted with the goal of enticing the visitor to explore the gallery section, where they can see these (and more) images better.
<!-- Insert screenshot of Home Page content here -->
- Social Media & External Links
  - The Bottom of the homepage contains links for Instagram and Bandcamp, where further work is hosted.
  - These include link descriptions to increase accessibility and hover responsivness to improve user feedback.

![Social Media links](/assets/readme_images/social_links.png)

- Gallery
  - The gallery will show examples of visual work completed by the artist.
  - Equally sized images are placed in rows, while irregulary sized images are placed centrally in their own row.
  - All images have some dark padding around the edges, intended to frame the images against the background.

![Gallery](/assets/readme_images/gallery.png)

- Contact form
  - The contact form is on the 'contact' page and provides an opportunity for visitors to get in touch with the artist, allowing space for them to leave name, email address and a message.

  ![Contact form](/assets/readme_images/contact_form.png)

- Form Submission Page
  - This pages confirms with the visitor that their form has been submitted.
  - It also lets them know they will get a response and gives them options to navigate back to the main site again.

![Form Submission](/assets/readme_images/form_submission.png)

- 404 Error Page
  - The 404 error page is where the visitor is sent if an incorrect URL is entered.
  - It let's them know there's a mistake in the URL and then gives them options to navigate back to the site.

![404 Error Message](/assets/readme_images/404_message.png)

### Features for future implementation
- Modal Images
  - Clicking on images to increase image size and create focus on one image
  - Also an opportunity to add captions to images without cluttering up the gallery
- Additional Pages
  - In the continuing development of this site, extra pages may be added that display other work. These could include:
    - Migrating Bio information to an 'About' page to reduce text on homepage
    - Add a 'Music' page where embedded players from Bandcamp and Soundcloud can be used to show more work.

## Testing

### Functionality Testing
- Chrome Developer tools and Mozilla Firefox Web Developer Tools were used throughout the development of the site to test functionality, diagnose and solve issues with responsivness and assist with styling work.


### Lighthouse Testing
![Lighthouse Test 1](/assets/readme_images/lighthouse_report_1.png)

![Lighthouse Test 1](/assets/readme_images/lighthouse_report1_ex2.png)

![Lighthouse Test 1](/assets/readme_images/lighthouse_report1_ex1.png)
- Testing using Lighthouse tool in Chrome Developer Tools provided a decent score but also suggested was to improve, Including:
  - Properly sizing images and serving them in a next-gen format to decrease load time for users
  - Move font awesome script from out of the body of the site as it is render-blocking
  - Efficiently Encode cover image to decrease load time
  - Add alt text or name for social media links to improve accessibility
  - Add meta text for SEO improvement
- These issues were addressed and some of them resolved, increasing the accessibility and SEO of the site.
  - The issues with performance caused by image sizing loading couldn't be fixed and are explained in the Unfixed Bugs section.

![Lighthouse Test 2](/assets/readme_images/lighthouse_report_2.png)


### Issues Faced during development
- Landing Page design:
  - The landing page design originally had a taking up the right hand side of the screen, with the biography on the left. This can be seen in the initial wireframe design:

![Landing page wireframe](/assets/readme_images/landing_page_wireframe.png)

  - While this worked well on large screens, it was difficult to make responsive for smaller screens. As a result a vertically orientated design was created, increasing the ease of making the site responsive and hopefully enticing scrolling.

- Extra Features:
  - As can also be seen in the wireframe above, there were initially plans for a search function, a 'Sound' page and a 'Blog'. These were removed in order to focus on creating a fucntional site first.

- Footer Position:
  - The footer tended to rise up and sit under the content, whereas I wanted it to sit at the bottom of the page:
 ![Footer Issue 1](/assets/readme_images/footer_position.png)
  - A solution was found on [Stack Overflow](https://stackoverflow.com/questions/643879/css-to-make-html-page-footer-stay-at-bottom-of-the-page-with-a-minimum-height-b) and setting the body style class display to flex and and flex-direction to column fixed the issue.


### Validator Testing
- HTML
  - No errors were detected when passing the site through the official [W3C Markup Validation Service](https://validator.w3.org/nu/?doc=https%3A%2F%2Feosull.github.io%2FProject-1-Portfolio%2F)
- CSS
  - No errors were detected when passing the site through the official [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Feosull.github.io%2FProject-1-Portfolio%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

### Unfixed Bugs
- Images causing performance and layout issues. 

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows:
  - In the Github repository, navigate to the Settings tab
  - From the source section drop-down menu, select the master branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment
- A live link for the site can be found here: [https://eosull.github.io/Project-1-Portfolio/]

## Credits
- The images and text used in the site are the artists own
- The icons used in the footer and on the home page were taken from [Font Awesome](https://fontawesome.com/)
- HTML and CSS lessons from [W3Schools](https://www.w3schools.com/) were used as reference when designing the site, for example implementing flexbox in the gallery or styling contact form.
- Code Institute materials were used to assist writing README file, such as the [README template](https://github.com/Code-Institute-Solutions/readme-template) and the [Markdown Cheatsheet](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- The Code Institute [Gitpod Full Template](https://github.com/Code-Institute-Org/gitpod-full-template) was used as a template to begin building this site
- Site responsivness visualised using [Am I Responsive?](https://ui.dev/amiresponsive)
