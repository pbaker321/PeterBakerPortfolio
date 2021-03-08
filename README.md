![2021-03-05 (5)](https://user-images.githubusercontent.com/75320149/110158530-65904780-7de1-11eb-99df-90e919f661fd.png)

# Peter Baker Portfolio Project


This is my First Milestone project for the [Code Institute](https://codeinstitute.net/). The aim is to create a personal portfolio using the skills i have learnt up to this point. The website will showcase the developers skills and creativity.

The deployed site can be seen [here.](https://pbaker321.github.io/PeterBakerPortfolio/)


## UX
 
This a beginner full stack developer website. The aim of the site is to promote the developer for future employment and potential projects.

This is a fully responsive website. Which can be used on many platforms and browsers.

### The target audience for the website.

- Potential Employers
- Users looking for help with websites
- Other developers looking for help with current projects

### User Stories

- As a User I want a clean but visually striking website, absent of clutter and unnescerarry clutter.
- As a User I want to see straight away visually see what the developer is capable of.
- As a User I want to learn a little bit about the developer.
- As a User I want to know what level of skills the developer has.
- As a User I want to be able to navigate my way through the site without using the back key.
- As a user I want to be able to see and download the developers CV.
- As a User I want to be able to see the developers previous projects.
- As a User I want to be able to see the developers repositories.
- As a User I want to be able to contact the developer.
- As a User I want to be able to go to the developers social media.

The Website will consist of 4 pages and a link to the developers CV.

The wireframes can be found [here.](https://www.figma.com/file/SYpJ97bFEnBfiS0DF3i0Rj/Portfolio)


## Features


### There will be:
 
- 4 pages consisting of:
    1. Home/Landing page. 
        - Striking landing page to gain the users attention.

    2.  About. 
        - Information about the developer. 
        - Developers skills. 
        - link to CV.

    3. Portfolio. 
        - An Image of the project.
        - A summary about previous projects.
        - Links to deployed site.
        - Links to project repositories.
        - What Technologies were used for the projects.

    4. Contact. 
        - A form to contact the developer for future projects or employment.

### Existing Features:
- Navigation Bar. Easily navigate to pages. Page is marked as active.
- Footer. Links to social media.
- Portfolio Page. Links to both the deployed site and to the repository
- Contact Form. (Not Fully Functioning)
- Downloadable CV. Opens in a separate Tab. (Mock CV)



### Features Left to Implement
- Functioning Contact form.
- Photography Portfolio.

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.

- [bootstrap4](https://getbootstrap.com/) - Layout & Responsiveness.
- [HTML5](https://en.wikipedia.org/wiki/HTML5) - Content & Structure.
- [CSS3](https://en.wikipedia.org/wiki/CSS) - Styling.
- [Github](https://github.com/) - Hosting the site.
- [Gitpod](https://www.gitpod.io/) - Developing the site.
- [Freepix](https://www.freepik.com/) - Images.
- [Fontawesome](https://fontawesome.com/v4.7.0/icons/) - Icons.
- [Googlefonts](https://fonts.google.com/) - Fonts.
- [TinyPNG](https://tinypng.com/) - Compressing Images.


## Testing

### Code Validator

- [HTML Validator](https://validator.w3.org/)
![html-check](https://user-images.githubusercontent.com/75320149/110157678-62488c00-7de0-11eb-97ca-b370686af533.png)

No Issues detected.


- [CSS Validator](https://jigsaw.w3.org/css-validator/)
![css-check](https://user-images.githubusercontent.com/75320149/110157604-48a74480-7de0-11eb-83e5-d4e2a3ea1191.png)

No Issues detected.

Tested on different Browsers.

**Test**|**Chrome**|**Mozilla**|**Opera**|**Edge**
:-----:|:-----:|:-----:|:-----:|:-----:
Links|Good|Good|Good|Good
Images|Good|Good|Good|Good
Renders|Good|Good|Good|Good

Responsiveness was tested using [Chrome developer tools.](https://developers.google.com/web/tools/chrome-devtools) and [Responsive Design Checker.](https://www.responsivedesignchecker.com)

**Responsiveness**|**Landing**|**About**|**Projects**|**Contact**
:-----:|:-----:|:-----:|:-----:|:-----:
Desktop <1200px|Good|Good|Good|Good
ipad Pro|Good|Good|Good|Good
ipad|Good|Good|Good|Good
iphone x|Good|Good|Good|Good
iphone 5/SE|Good|Good|Good|Good

## User Stories Testing.

1. As a User I want a clean but visually striking website, absent of clutter and unnescerarry clutter.
    - Landing page, tells the User who is the developer.
    - Background iamge and colors draw in the User.
    
2. As a User I want to see straight away visually see what the developer is capable of.
    - Using an interesting background.
    - Background doesnt ditract the User.
    - Good colors, allow it to visually pleasing to the eye.

3. As a User I want to learn a little bit about the developer.
    - Home page has a very brief about me.
    - About page gives more information.
    - Reasons given to why the developer should be hired.
    - Link to the CV for full information.

4. As a User I want to know what level of skills the developer has.
    - Progress bar names the skills and the level of knowledge the developer has.

5. As a User I want to be able to navigate my way through the site without using the back key.
    - Navigation bar will bring the user to the required page.
    - Navigation bar will turn into the "hambrger icon" when using on handheld devices.

6. As a user I want to be able to see and download the developers CV.
    - Downloadable link on the About page.
    - Link has an download icon, as to be clear of its function.

7. As a User I want to be able to see the developers previous projects.
    - A button clearly labelled to github under the required project.

8. As a User I want to be able to see the developers repositories.
    - A button clearly labelled to github under the required project.

9. As a User I want to be able to contact the developer.
    - There is a contact page 
    - An easy to use form asking for relevant Information.
    - Any missing Information, the form will not submit and the required field will be flagged.

10. As a User I want to be able to go to the developers social media.

### Bugs

1. Project page. When looking at responsiveness, the images wouldnt line up properly. 
And the breakpoints were at the wrong places.
    - Used bootstrap for the columns breakpoint. 

2. Footer. I was unable to get the footer to stay at the bottom of all pages.
    - On CSS I changed the min-height on body to 100vh.

3. Images. Images wouldnt show after i deployed the site. 
    - I adjusted the file route.



## Deployment

#### How I deployed my first milestone project

- Go to [Github](https://github.com/)
- Log into my account.
- Click on repositories.
- Click on Peter Baker Portfolio.
- Select settings.
- Scroll down to Github pages section.
- Under source click "none" and select "Master Branch".
- Click save.
- Scroll back to the Github pages section and the link to the deployed site is there.

#### How to run the code locally.

1. On [Github](https://github.com/), navigate to the main page of the repository.
2. Above the list of files, click Code.
3. Copy the URL on HTTPS by clicking the clipboard.
4. In your IDE of choice, open Git Bash.
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type git clone, and then paste the URL copied from [Github](https://github.com/).
7. Press enter and the local clone will be created.



## Credits

### Media

- The Background image used in this site was obtained from  [Freepik](https://www.freepik.com/)

### Contents

- Navigation using [bootstrap4.](https://getbootstrap.com/)
- Contact Form using [bootstrap4.](https://getbootstrap.com/)

### Acknowledgements

- My mentor Precious Ijege 
- [Thiago Hardt](https://github.com/ThiagoHardt) For all the patience and advice.