# Trave

Trave is the bridge for construction companies looking to streamline their project management and financial processes. Trave is a software development company bringing technology and construction together, providing a seamless and efficient experience for our clients. With Trave, you'll be able to transform the way you manage your projects and finances, saving time and money in the process.

[Link To Live Website](https://conroy9068.github.io/project-1-trave-website/index.html)

![Responsice Mockup](https://github.com/conroy9068/project-1-trave-website/blob/main/assets/images/readme-images/responsiveness.png)

### Existing Features

- __Navigation Bar__

	- The navigation bar can be found on all three pages. This includes links to each section of the index page, and contact page. It can be found on each pages of the website to allow for easy navigation.
	- The naviagtion bar is fully responsive to allow user to browse from all devices with ease. 

![Nav Bar Desktop](https://github.com/conroy9068/project-1-trave-website/blob/main/assets/images/readme-images/desktop-nav-bar.png)
![Nav Bar Mobile](https://github.com/conroy9068/project-1-trave-website/blob/main/assets/images/readme-images/mobile-nav-bar.png)

- __The landing page image__

	- The landing page displays cover text that explains what Trave helps construction companies achieve. To the right of that cover text we can see an image of a crane and some building under construction.
	- The background has another image that shows more cranes and buildings.

![Landing Page](https://github.com/conroy9068/project-1-trave-website/blob/main/assets/images/readme-images/hero-section.png)

- __Challenges Section__

	- The challenges section shows three common challenges construction companies face.
	- Controlling Labour & Material Costs, this is one of the biggest issues in the construction industry. Not know if a project is over or under budget through its lifespan.
	- Time consuming Admin, mondane tasks that task hours of work and with todays technology can be automated allowing that user to focus on more pressing tasks.
	- Unconnected Software Packages, many companies have multiple solutions doing different things leading to data silos which can be hard. to analyse.
	- These three pain points with help the client relate and encourage them to find the solutions section.

![Challenges Section](https://github.com/conroy9068/project-1-trave-website/blob/main/assets/images/readme-images/challenges-section.png)

- __Solutions section__

	- This section highlights what can be possible and how Trave can help the user gain control over the challenges listed in the previous section. 

![Solutions Section](https://github.com/conroy9068/project-1-trave-website/blob/main/assets/images/readme-images/solution-section.png)

- __Value Proposition section__

	-The value proposition section lets the user know the steps they can take to get started in order to start their digital transformation. 
	- They can click the "Schedule A Meeting" button to navigate to the contact form to submit their details to request a meeting.

![Value Proposition Section](https://github.com/conroy9068/project-1-trave-website/blob/main/assets/images/readme-images/value-prop-section.png)


- __The Footer__ 

- The footer section shows the various social media platforms they can follow to stay up to date with the latest new with Trave.
- The links will open in a new tab using the target="_blank" attribute.

![Footer](https://github.com/conroy9068/project-1-trave-website/blob/main/assets/images/readme-images/footer.png)


- __Contact Page__

	- The contact page enables users interseted in setting up a meeting with Trave. The user can add their details and a message detailing what they are looking to achieve.
	- The form contains validation requiring the user to enter their name and a valid email.

![Contact Page](https://github.com/conroy9068/project-1-trave-website/blob/main/assets/images/readme-images/contact-page.png)
![Form Validation Sample](https://github.com/conroy9068/project-1-trave-website/blob/main/assets/images/readme-images/form-validation.png)

### Features Left to Implement

- A feature I would add is quick links to the footer.
- I would like to have added circle containers above each of the steps with the numbers 1, 2 and 3 along in the Value proposition section

## Testing 

- Testing was carried out on all three pages of the website. The testing was carried out on the following devices:
	- Desktop
	- Mobile

- The testing was carried out on the following browsers:
	- Chrome
	- Firefox
	- Safari

- Navigation bar testing was done across all screen sizes using the option to resize the browse window within chrome dev tools. The navigation bar was tested to ensure that it was responsive and that the links worked as expected.
- The landing page image was tested to ensure that it was responsive and that the text was readable across all screen sizes.
- The challenges section was tested to ensure that each card stacked accordingly to the differnt screen size and that the images where not distorting.
- The testing on the solutions section was just like the challenges section. Text was tested to ensure that it was readable and that the images were not distorting.
- The value proposition section was tested to ensure that the text was readable and that the button was responsive. The button was tested to make sure it also worked correctly.
- The footer was tested to ensure that the social media icon links opened in a new tab and linking to the correct website. The footer was also tested to ensure that it was responsive across all screen sizes.
- The contact page was tested to ensure that the form was responsive and that the validation was working correctly. The form was tested to ensure that the submit button was working correctly and it succsefully naviagted to the form-submission.html page.
- The form submission page was tested to ensure that the text was readable across all device screen sizes. 
- Trave logo text was noting link to index.html page. I had positioned the logo outside of the nav tag. I moved the logo inside the nav tag and the link worked as expected.
- Scheduale A Meeting button was overlaying the navigation menu when the nav menu is open on mobile. This was fixed by moving the meeting button div container into the correct position and fixing the css.


- Lighthouse testing was carried out on all three pages of the website. The testing was carried out on the following devices:
	- Desktop
	- Mobile

[Desktop Home](https://github.com/conroy9068/project-1-trave-website/blob/main/assets/images/readme-images/readme-html-pages/desktop-home-test.html)

### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://github.com/conroy9068/project-1-trave-website/blob/main/assets/images/readme-images/html-validation.png)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://github.com/conroy9068/project-1-trave-website/blob/main/assets/images/readme-images/css-validation-results.png)

  ### Unfixed Bugs

- On modile devices the nav bar will stay open when on the index page trying to browse differnt sections. It will close if you move between the three html 		pages. Reasearch was done and a possible fix was found using javascript. However, I was unable to implement this fix in time.
- The nav bar will stay open on mobile device when on the index page trying to browse differnt sections. It will close if you move between the three pages. 
- The hero image on small devices is not responsive. The top of the image begins to cut off.
	![Hero Image Cut Off](https://github.com/conroy9068/project-1-trave-website/blob/main/assets/images/readme-images/hero-img-hidden-on-sml-dev.png)
- The footer on the form-submission.html page is not sticking to the bottom of the page where i would like it. 
- The footer overlays on the nav menue on mobile view when viewing the form-submission.html page.
- favicon is not displaying on the browser tab

## Deployment

- The process for setting up this site using GitHub pages was as follows: 
  - Log in to GitHub and locate the GitHub Repository 
  - At the top of the Repository (not top of page), locate the "Settings" Button on the menu. 
  - On the left-hand side of the Settings page, under the code and automation section, click on "Pages".
  - Under "Source", click the dropdown called "None" and select your master branch. 
  - On the right hand side of the page, under "Enviroments", you will see a link to the deployed site.

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - ![Link to live site](https://conroy9068.github.io/project-1-trave-website/)

### Content 

- [Responsive nav bar tutorial](https://www.codingnepalweb.com/responsive-navigation-menu-bar-html-css/) - This tutorial helped me build a responsive nav bar.
- [Responsive form section with validation](https://www.youtube.com/watch?v=nwEB3Wxh5N0) - This tutorial helped me build a responsive form section with validation.
- [A guide to flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This guide helped me understand flexbox and how to use it.
- [Flexbox Frogy](https://flexboxfroggy.com/) Teaching tool for flexbox
- The content for the website was taken from [Trave](https://www.trave.io)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
- This tutorial helped me implement a favicon for the website. [Favicon Tutorial](https://www.w3schools.com/html/html_favicon.asp)

### Design

The design for this website was taken from the current company website for Trave. ![Link to current site](https://www.trave.io). My goal was to capture the same structure and layout of the current website while adding my own personal touch.

The new Trave website allows user to navigate through the sections on the home pages. The current website does not allow the user to navigate through the sections on the home page. 

#### Wireframes

The wireframe was created in figma. The wireframe was created using the current Trave website as a guide. 

![Wireframe](https://github.com/conroy9068/project-1-trave-website/blob/main/assets/images/readme-images/wireframe.png)

#### Colours

The colour palette was created using [Adobe Color](https://color.adobe.com/create).

![Colour Palette](https://github.com/conroy9068/project-1-trave-website/blob/main/assets/images/readme-images/color-palette.png)

#### Typography

The Font is Montserrat 300 from [Google Fonts](https://fonts.google.com/specimen/Montserrat?query=mont) This font was chosen because its the same font used in the company logo but with silighly differnt characteristics.

### Media

- The photos used on the home and sign up page are from This Open Source site [Unsplash](https://unsplash.com/)
- There is also some graphics taken from the Trave website. [Trave](https://www.trave.io)
