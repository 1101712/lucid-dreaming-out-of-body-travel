# LUCID DREAMING

Lucid Dreaming is a site that hopes to help people learn what are lucid dreams  and what science says about them. With the help of a test on a link on a third-party website, you can find out your individual predisposition to lucid dreams. My site hopes to encourage people to get their own personal experience of awareness in a dream. To do this, there is a link to a third-party website with detailed step-by-step instructions.

![alt text](screenshot-copy.jpg "This are screenshots of pages of the website")
 ## Features
My site has 4 pages. All of them are devoted to the topic of lucid dreams.
The main page contains the main image with the zoom effect and common information about lucid dreams.
The second page provides information about what lucid dreaming is, techniques for starting practice and links to official free books.
The third page informs the visitor about the scientific side of this issue.
The fourth page hopes to keep visitors motivated to try the practice of lucid dreaming. There is also a video on this page.

## Existing Features

+ Navigation Bar
  + Featured on all four page, the full responcive navigation bar includes links to the Home page, Lucid Dreaming page (About), A Scientists View page (Science), Why Not page (Thoughts) and is identical in each page to allow for easy navigation.
  + This section will allow users to easily navigate across all devices without having to revert to the previous page via the "back" button.
+ The landing page image
  + The landing includes an image with an animation effect. Thanks to this, visitors of the site can feel the effect of being involved in the plot of the image, immersion in another reality, reality of lucid dreaming.
  + Further, after a brief definition of a lucid dream, there is an image of a keyhole and three buttons below it, which duplicate navigation, but represent a more aesthetic solution in the form of buttons with more detailed text on them.
This should intrigue users and stimulate their interest in getting more detailed information.
+ The Lucid Dreaming page 
    + The page is designed with a Midjourney-generated image of a possible lucid dream plot. The image is followed by a description of a typical subjective experience of falling into a lucid dream. After that, the user is asked to click on the buttons, which are links to third-party sites with more detailed information. To represent their role, those buttons have an animated "hover feature" with arrows appearing when user hovers her cursor over them. These buttons will open the link in a new window, so that the user stays on the website after checking out the suggested external content.
+ The Scientists view page is designed with an sign-kind-image. This sign should cause a subconscious association with more official information. The general concept and design of this page repeats the conceptual solution of the page described above.
+ The Why Not page 
   + This page should encourage users to consider lucid dreaming as their new expierence. To do this, a video with a short text below it is embedded in the page. Design the video allow users to initiate and control the playing of it. 
   + At the end, a short survey is embedded on site in the form of a checkbox. By doing this, I make it clear to site visitors that their opinion is important to me.
   
## UX
### Site goals
The purpose of the Lucid Dreaming website is to introduce users to lucid dreaming. Those who already have experience of lucid dreams may be able to find additional detailed useful information.

Users are also given the opportunity to
take a test for a predisposition to lucid
dreaming on a third-party website.The test is available on the website of the research laboratory, the results of which are published in specialized scientific journals.

It is also the goal to make it easy to users to find all the nesessary and trustworthy information in one place. The site should be easily to navigate as well as aesthetically pleasing.

The three types of buttons enable an intuitive UX
1. The first type are buttons representing internal links, and they are separate from the usual navigation
menu. The "hover feature" simply underlines the button when user hovers her cursor over them. This
highlights the fact that the button is an active link.
2. The second type are buttons leading to other websites. To represent their role, they have an animated
"hover feature" with arrows appearing when user hovers her cursor over them. These buttons will open
the link in a new window, so that the user stays on the website after checking out the suggested external
content.
3. The third type is the "Submit" button in the UX survey. It does not have a "hover feature" due to it not
being an active link. The "action" method is empty as of now, due to this project still being its early stage.
- I do not have a server to receive the submitted surveys.
Another aspect is that by default, buttons are not links. To override this, I used my CSS knowledge. In
order to make my buttons to also be active links, I have used the method **get** and pasted the link in
the action. So since there is no "form" to be submitted, the button will now open the link mentioned in the
"action".

#### Dupes of the navigation
Stilistically speaking, the navigation should be attached to the top of the page. However, on the main
(index) page you will see that the navigation is duped at the bottom of the page. It was a design desicion
of mine,

#### Accessibility
As a part of my commitment to the disabled community, all relevant images have alternative text
attached to them. 




## Technologies used
#### Languages used
- [HTML5](https://de.wikipedia.org/wiki/HTML5)
- [CSS3](https://www.w3.org/Style/CSS/)
#### Frameworks, Libraries & Programs used

1. [Google Fonts](https://fonts.google.com/specimen/PT+Sans)
- The "Google fonts" tool was used to impoirt the fonts into the style.css file, which is used in this project.
2. [PT Font Family](https://company.paratype.com/pt-sans-pt-serif)
- The fonts from the PT Family were chosed to make the website futureproof. As already mentioned, I
plan on adding multilanguage support to this project, and the Paratype fonts are built around non-latin
characters, such as the Cyrillic alphabet and special charachters used in post-Soviet countries, which
are very rare to find in fonts produced in the anglophone world. While dealing with an impressive amount
of letters from different language families, the PT font never compromises on aestetics - it has been
created by the internationally acclaimed typeface designer [Alexandra Korolkova]
(https://en.wikipedia.org/wiki/Alexandra_Korolkova) and Olga Umpelova.
However, should the project grow big enough to be translated into east-Asian or south-Asian languages,
new fonts shall be added to support, for example, Japanese or Thai fonts.
