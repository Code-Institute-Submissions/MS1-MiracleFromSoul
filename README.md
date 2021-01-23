<h1 align="center">Code Institute Milestone Project 1 - "Miracle from Soul"</h1>

![Miracle from Soul Mockup](documentation/MfS-mockup.jpg)

Click [here]() to see live project.

# Miracle from Soul

Miracle from Soul is a website of an polish artist, who is selling their paintings in Ireland.

Website will not only present the existing work of the artist, allow the user to purchase the art 
(feature to be introduced later), but also allows users to contact the artist and by providing inspirations, order the
personalized piece of art - via contact section.

# Table of Content

1.  [User experience](#user-experience)
    - [User Stories](#user-stories)
    - [Design](#design)
    - [Wireframes](#wireframes)
2.  [Features](#features)
    - [Existing Features](#existing-features)
    - [Features left to Implement](#features-left-to-implement)
3.  [Technologies](#technologies)
4.  [Languages](#languages)
5.  [Frameworks](#frameworks)
6.  [Libraries](#libraries)
7.  [Other](#other)
8.  [Testing](#testing)
9.  [Bugs](#bugs)
10. [Deployment](#deployment)
11. [Credits](#credits)

# User Experience

## User Stories

This website is for people interested in purchasing paintings made by particular polish artist.

Website will be advertised via artists facebook page as another platform for viewing and purchasing art.

 - Users interested to find out about the artist will have a chance to find out about artist's story and inspirations in **About** section.

 - Users interested in viewing art will have access to artist's gallery in **Gallery** section.

 - Users interested in purchasing art will have a chance to add items from the gallery into basket, a feature that will be added in a later stage of development.

 - Users interested in ordering personalized painting form the artist will have a chance to explain what they need in **Contact** section.

All users will have a opportunity to contact artist via their **social media** accounts and **contact form**.

## Design

### Templates

- Website uses bootstrap single page application template called "Mentor" taken from [here](https://bootstrapmade.com/mentor-free-education-bootstrap-theme/). Template was heavily customize by me for the purposes of this project.

- Single page application was used to assure the structure 
- Template contains series of links to libraries stored in files that I have copied from the template's folder (folders "vendor" and "js" in assets).

- Contact form template came from [Bootsnipp](https://bootsnipp.com/snippets/5KRq8) and was created by a user name "kastya".

- Template also contains some script links below the footer. Those also came in package.

### Colour

- Colour palette used for this project was taken from [](https://www.w3schools.com/colors/colors_shades.asp).

- All colours used for this project are in shades of gray: Nero (#282828), Gray77 (#C4C4C4), Whitesmoke (#F5F5F5).

- Additional colour were used for hover effect: Matterhorn (#505050), Gray88 (#E0E0E0), Nobel (#989898), Trolley Gray (#808080)

- Greyscale was used to expose the colourfulness of artist's work and the environment they operate in.

![Color Palette](/assets/project/color-palette.JPG)

### Typography

- [Font](https://fonts.google.com/) Caveat Brush was used throughout the project, as per artist's advice to keep it consistant with the logos artist is using outside this page.

- [IcoFont](https://icofont.com/) icons for social media links in footer were imported along with the single page application template 

### Images

All images come from the pictures taken by the artist herself:

- "Hero" image and all images in "Gallery" section of the website present the work of art done by the artist.

- Portrait image in "About" section of the website presents the artist herself.

- "Studio" image in "About" section of the website presents the studio in which artist works.

## Wireframes

- Wireframe was developed using [Figma](https://www.figma.com/)

- Wireframe of this single page application can be seen [here](https://www.figma.com/proto/lThdyqeH1xkHiQkp9kkOMN/Miracle-from-Soul?node-id=22%3A17&scaling=min-zoom)

[Top](#table-of-content)
# Features

Website allows user to find out about the artist's life and inspirations, view their work and contact them.

## Existing Features

- **About** - allows users to find out about the artist, their life and inspirations.

- **Gallery** - allows users to view artist's work, find out information about each individual painting (work's title & size of painting).

- **Contact** - allows users to send email directly to artists. Users are encouraged to order personalized piece of art, to provide links and ispirations to help artist understand what users need.

## Features Left to Implement

- **Purchase** - feature will be added, allowing users to purchase pieces of art directly via website. **Buy** button will be added to each individual image in gallery and the trolley icon will be added in header.

- **EN/PL** - feature will be added, allowing users to switch between English and Polish version of the website, where the whole content will be translated to Polish language.

[Top](#table-of-content)
# Technologies Used

- [HTML](https://www.w3schools.com/html/html_intro.asp)
    - to provide content to a website.

- [CSS](https://www.w3schools.com/css/)
    - to provide style to the content of the website.

- [Figma](https://www.figma.com/)
    - to provide wireframe.

- [Mentor](https://bootstrapmade.com/mentor-free-education-bootstrap-theme/)
    - to provide template framework to this website.

- [Bootsnipp](https://bootsnipp.com/snippets/5KRq8)
    - to provide template framework for the contact section of this website.

- [IcoFont](https://icofont.com/)
    - to provide icons to the website.

- [Google Fonts](https://fonts.google.com/)
    - to provide free font to the website.

[Top](#table-of-content)
# Languages

- [HTML5](https://en.wikipedia.org/wiki/HTML5)

- [CSS](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

[Top](#table-of-content)
# Frameworks

- [Bootstrap](https://getbootstrap.com/)
    - technology was used throughout the pages.

- [Mentor](https://bootstrapmade.com/mentor-free-education-bootstrap-theme/)
    - to provide template framework to this website.

- [Bootsnipp](https://bootsnipp.com/snippets/5KRq8)
    - to provide template framework for the contact section of this website.
    
[Top](#table-of-content)
# Libraries

- Libraries used in the project came along with the [template](#templates).

[Top](#table-of-content)
# Other

## Excessive code

Due to the use of [templates](#templates), some extra code that seems excesive, can be found throughout the project. 
I removed the parts of the code that seemed unnecessary, since whole sections were removed while styling templates 
for the purposes of this project. Some parts of the code still seem unrelated to the project, but when removed cripple 
the website in some ways and cause issues with styling, layout or functionality. I have allocated hours at the time to 
find out which lines of code can be removed, kept refreshing the site and checking functionalities in mobile, tablet and 
desktop view.

## Lessons learned

The use of bootstrap templates theoretically makes work more efficient, since it provides big parts of code. However, if
one does not posesses in-depth knowledge of the topic, it can be then time consuming to then tailor the code for ones own
purposes.

In the process of removing the excessive code, I have reduced half the lines of code in both index.html and style.css files.
However, through trial and error, I found out that certain lines of code, even tough they seemed unrelated, when removed,
cause certain parts of website to crash.

[Top](#table-of-content)
# Testing




In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

[Top](#table-of-content)
# Bugs
## Found and fixed ?????
## Not fixed ?????
[Top](#table-of-content)
# Deployment

## Begining

- I have used the cloud-based IDE [Gitpod](https://gitpod.io/) and [GitHub](http://github.com/) as a free git repository hosting.

- As first step, I have installed the [Gitpod extension](https://chrome.google.com/webstore/detail/gitpod-dev-environments-i/dodmmooeoklaejobgleioelladacbeki) for Chrome browser that I use.

- Next, I created repository on [Github](https://github.com/) using the gitpod template provided by the [Code Institute](https://github.com/Code-Institute-Org/gitpod-full-template).

- Then, I clicked on "Gitpod" button, which opened workspace in Gitpod, where I created my project.

- Once in Gitpod, the following commands were used while developing this project:
    - "git add (file name)" - to add files for staging.
    - "git status" - to see what is the current status of directory and staging area.
    - "git commit -m "(description of action taken)" - to commit changes along with short comment of what was done.
    - "git push" - to push commits to Github.
    - "python3 -m http.server" - to open ports allowing me to view the current state of the website in Chrome.

## Running project locally

- In order to run this project locally, follow the below steps:

    - Click on the [link](https://github.com/LucasCegielski/MS1-MiracleFromSoul) to this project's repository in GitHub (you must be logged into your own Github account).
    - Click on the dropdown menu Code button located next to green "Gitpod" button.
    - Click on "Open with GitHub Desktop" to clone and open the repository locally.
    - Click on the "Choose" option and navigate to the local path where the cloned repository should be located.
    - Click "Clone"

- For more details on how to clone repository in Github click [here](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository).

[Top](#table-of-content)
# Credits

## Content

- The quote on the home page comes from Frieda Khalo.

- The text for sections was written by myself.

## Media

- The photos used in this site were obtained from the artist's [Facebook website](https://www.facebook.com/MiracleFromSoul) and were provided from private collection, by the artist herself via email.

## Acknowledgements

- My Mentor Seun, for help and inspirations.

- My Mentor Aaron, for help and inspirations (for organizational purposes my Mentor was replaced on my request).

- Tutors for feedback, much appreciated help and guidance. 

- My Sister, the artist, for pictures, some good ideas and inspirations.

- [Stackoverflow](https://stackoverflow.com/), Slack and Github communities for feedback and troubleshoot throughout.

[Top](#table-of-content)