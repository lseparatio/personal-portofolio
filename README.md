# Ionut Zapototchi Personal Portfolio

Welcome, this project is proof of my skills as a developer. This is also a real project where all the projects I worked on will be posted in time, this serving as my portfolio. This project is also designed so that people who want to hire me can get a better idea of my skills and be able to contact me as easily as possible.

See this project on live enviroment on GitHub Pages here: <https://lseparatio.github.io/personal-portofolio/>

![Website on different screen sizes](readme-assets/img/screens.png)

## Features

<details>

<summary>Click To Expand Features</summary>

### Navigation

- Same navigation menu is used across all pages for consistency.

![NavBar Desktop](readme-assets/img/navbar-desktop.jpg)

- Navigation was designed to be easy to use and to understand.

![NavBar Mobile](readme-assets/img/navbar-mobile.jpg)

- Navigation was aswell designed to work wall on all devices.

### Index Page - Hero Section

 ![Hero Image](readme-assets/img/hero.jpg)

- Hero section have a nice background image with a overlay text, my name and site purpose.

### Index Page - Welcome Section

![Welcome Section Screen](readme-assets/img/welcome.jpg)

- Welcome section have my image and a welcome and presentation text.
- The section is designed to welcome the potential employer and to give him a better idea about who i am.

### Index Page - Skills Section

![Skills Section](readme-assets/img/skills.jpg)

- Skills section was designed to show in a nice manner to an possible employer my set of skills.

### Index Page - Call to Action Section

![Call to Action Section](readme-assets/img/call-to-action.jpg)

- Call to Action Section was designed to do not lose the reader attention and to help him in a easy way to next page.
- This section contain a text and a button that is sending user to next page.

### Work Example Page

![Work Example Page Desktop](readme-assets/img/work-examples.jpg)

- Work Examples page was designed to show all my projects to the user, to provide with some basic information about projects.
- There are 2 buttons to every work example, first leading to Live project page and second to GitHub project.
- User can change the content by selecting the domain of expertise.
- Page is completely responsive:
- Phone example:

![Work Example Page Phone](readme-assets/img/work-examples-mobile.jpg)

- Tablet Example:

![Work Example Page Tablet](readme-assets/img/work-examples-tablet.jpg)

### Contact Page - Social Icons Section

![Contact Page Social Section](readme-assets/img/fancy.jpg)

- In order to create a connection with reader, i have to "Speack with him", this is what is doing this section.
- Also i provide with 6 contact ways.

### Contact Page - Contact Form

- But if all that contact ways are not enough..

![Contact Form](readme-assets/img/contact-form.jpg)

- ...an contact form, contact detaills and map need to be provided.
- All page is full responsive.

### Thank You Page

![Thank You Page](readme-assets/img/thank-you-page.jpg)

- Thank you page where user is redirected after form is succesfully submited.

### Custom 404 Page

![Custom 404 Page](readme-assets/img/404-page.jpg)
</details>

## The Creation Timeline

<details>
<summary>Click to open creation timeline</summary>

### User Stories

As a site owner:

- I want users to understand fast that this website is for my portfolio.
- I want users to be able to easily navigate my website on any device.
- I want to present myself as best as possible including my skills.
- I want to be easy to contact on multiple platforms.
- I want my website to be accessible to anyone even for screen readers.

As a user:

- I want to be able to view the website on any device.
- I want the menu to be intuitive.
- I want to learn as much is possible about developer.
- I want to know what skills have the developer.
- I want to see what other projects developer did.
- I want to find out who you are.

### Wireframes, i used Balsamiq

<details>

<summary>Click to expend wireframes</summary>

- Mobile Wireframes:

 1. Index Page

![Index Mobile Example](readme-assets/wireframes/index-page-mobile.png)

 2. Example Page

![Example Mobile](readme-assets/wireframes/work-examples-mobile.png)

 3. Contact Page

![Contact Mobile Example](readme-assets/wireframes/contact-mobile.png)

- Tablet Wireframes:

 1. Index Page

![Index Tablet Example](readme-assets/wireframes/index-page-tablet.png)

 2. Example Page

![Example Tablet](readme-assets/wireframes/work-examples-tablet.png)

 3. Contact Page

![Contact Tablet Example](readme-assets/wireframes/contact-tablet.png)

- Desktop Wireframes:

 1. Index Page

![Index Desktop Example](readme-assets/wireframes/index-page-desktop.png)

 2. Example Page

![Example Desktop](readme-assets/wireframes/work-examples-desktop.png)

 3. Contact Page

![Contact Desktop Example](readme-assets/wireframes/contact-desktop.png)
</details>

### Tools

- Visual Studio Code ( After i tried some editors it seem i like visual studio and the fact it is saving a local copy of project and i can push to GitHub. )
- GIMP ( For image editing. Briliant open-source editor. )
- Bootstrap 4.6 ( I did this choice after i read in Bootstrap 5 documentation that they have problems with Internet Explorer. )

### Colors

- I used <https://coolors.co/image-picker> to pick a color  from my profille image.

  ![Color Picker](readme-assets/img/coolors.png)

### Images

- Images was taken from <https://www.pexels.com/>
  
</details>

## Coding

- The coding progress can be seen on commits.

- In coding progress Bootstrap documentation was indespensable.

## Testing

I started the testing using for LightHouse from Google. I learn  that even from an expert like google you can't expect exact results every time. So i am going to show you here the best result. Even some time performance is droping to 80 because they can't acces bootstrap css ?!?

<details>
<summary>LightHouse front page for Mobile test, click to expand.</summary>

![LightHouse test front page](readme-assets/img/tests/lighthouse-frontpage.png)
</details>

<details>
<summary>LightHouse front page for Desktop test, click to expand.</summary>

![LightHouse test front page](readme-assets/img/tests/front-page-desktop.png)
</details>

## Fixes after testing with lighthouse

- I learn in the hard way that converting a JPG to WEBP is not always usefull, the image can be even heavier after conversion in some cases. For this reason i had to change hero image because whas a bit more that 2mb. Now i have a 187 KB image that boosted the performance.

- Thanks to lighthouse i learn to add rel="noopener" to any target="_blank" for security. So thanks.

### Examples Page

<details>
<summary>LightHouse example page for Mobile test, click to expand.</summary>

![LightHouse test mobile example page](readme-assets/img/tests/exaple-page-mobile.png)
</details>

<details>

<summary>LightHouse example page for Desktop test, click to expand.</summary>

![LightHouse test mobile example page](readme-assets/img/tests/example-page-desktop.png)
</details>

- was no so much to fix here only that rel="noopener" in all links.
- can be done to reduce images sizes, but 10 is for teachers.

### Contact Page

<details>
<summary>LightHouse example page for Contact page test, click to expand.</summary>

![LightHouse test mobile example page](readme-assets/img/tests/contact-mobile.png)
</details>

<details>

<summary>LightHouse example page for Contact Page Desktop test, click to expand.</summary>

![LightHouse test mobile example page](readme-assets/img/tests/contact-page-desktop.png)
</details>

## Validator testing

- No errors were returned when passing through the official validator.

### Front page validator link: <a href="https://validator.w3.org/nu/?doc=https%3A%2F%2Flseparatio.github.io%2Fpersonal-portofolio%2Findex.html" rel="noopener" target="_blank">Click To See</a>

<details>
<summary>Click to expand image.</summary>

![W3 validator check for front page with no errors](readme-assets/img/tests/front-page-w3.png)
</details>

### Examples page validator link: <a href="https://validator.w3.org/nu/?doc=https%3A%2F%2Flseparatio.github.io%2Fpersonal-portofolio%2Fexamples.html" rel="noopener" target="_blank">Click To See</a>

<details>
<summary>Click to expand image.</summary>

![W3 validator check for examples page with no errors](readme-assets/img/tests/example-page-w3.png)
</details>

### Contact page validator link: <a href="https://validator.w3.org/nu/?doc=https%3A%2F%2Flseparatio.github.io%2Fpersonal-portofolio%2Fcontact.html" rel="noopener" target="_blank">Click To See</a>

<details>
<summary>Click to expand image.</summary>

![W3 validator check for contact page with no errors](readme-assets/img/tests/contact-page-w3.png)
</details>

### Thank you page validator link: <a href="https://validator.w3.org/nu/?doc=https%3A%2F%2Flseparatio.github.io%2Fpersonal-portofolio%2Fthank-you.html" rel="noopener" target="_blank">Click To See</a>

<details>
<summary>Click to expand image.</summary>

![W3 validator check for thank you page with no errors](readme-assets/img/tests/thank-you-page-w3.png)
</details>

### CSS validator link: <a href="https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Flseparatio.github.io%2Fpersonal-portofolio%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en" rel="noopener" target="_blank">Click To See</a>

<details>
<summary>Click to expand image.</summary>

![W3 validator check for css with no errors](readme-assets/img/tests/css-w3.png)
</details>

## Deployment

### This website was deployed on GitHub pages. Steps

- In the GitHub repository, navigate to the Settings tab
- In left menu, down find Pages tab
- From the source section drop-down menu, select the Main Branch
- Once all is done your link is displayed.

This particular deployment can be seen on: <https://lseparatio.github.io/personal-portofolio/>

### This website was deployed on VPS server. Steps

- after you setup vps or shared hosting and a domain name, in the GitHub repository press CODE dropdown and then Download ZIP.
- upload the ZIP in your public_html folder and un-zip-it.  You shud have the website ready.

Example of this deployment can be seen on: <https://ionutzapototchi.com>
(This version is identic with GitHub Pages hosted excepting php code source that is making the form to send emails. <https://www.freecontactform.com/forms/contact-form-free>)

## Credits

- Bootstrap - For well documented css framework
- Pexels - For hero photo (exaples photos have credits straight on page)
- Coolors - For color from image picker
- GIMP - For Image processing
- Favicon.io - For Favicon
- Font Awesome - For icons
- Google Fonts - For Lora font.
- Code Institute - For brilliant lessons from where i learn to do this.
- And Free Contact Form that provided me with php code with is making the form in my VPS hosted website to work. <https://www.freecontactform.com/forms/contact-form-free>

## Thank you for reading. For any questions don't hesitate to contact me. Kind Regards, Ionut Zapototchi
