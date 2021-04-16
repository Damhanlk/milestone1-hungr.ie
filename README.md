Read me Document Hungr.ie Project - User Centric Frontend Development - Code Institute & UCD Professional Academy
Introduction
Read me Document

## Hungr.ie

Project - User Centric Frontend Development - Code Institute & UCD Professional Academy

The project will cover a food centred site based in Dublin. The site aims to raise awareness of events taking place that week in the city, showcase photos of food submitted by users and highlight a featured recipe from a featured chef that week.

The idea behind the project comes from a personal interest in food and what a user such as myself would like to see as an all encompassing site for to easily see what has been happening and is happening in the city food wise. Users can visit the site to keep up to date with events and special offers, to sign up to the newsletter. Both new and returning users can also take advantage of the featured section which showcases recipes from that week for users to try at home.



A deployed link to the website can be found HERE https://damhanlk.github.io/hungrie-milestone1/

## UX

User Stories

The end user of this project is anyone either interested in food or coming to Dublin as a tourist or visitor. The site is aimed at varying age groups - generally younger people / couples who want to dine out in the city. The site would mainly be accessed on mobile.

The end user wants information on what events are taking place around the city and to click through to participating restaurants’ sites. The end user also wants to be able to return to hungr.ie as a base to collect information about recipes or chef’s that are being featured that week.

The benefit of this project is that it stores several features on one easily accessible and inviting homepage which is easily navigable for the user. It caters to both new and existing users by prompting to sign up for the newsletter.

As a user I want:

Clear and concise info on the 3 featured restaurants An easy to follow recipe with picture A bio on a featured chef that week I want directions to hungr.ie HQ in Dublin in order to find out more info. I want to be able to find contact details and social links easily in the footer I want to be able to view the site on my mobile device and tablet.

## Strategy

User needs - The user needs to be able to use all of the capabilities of this site on mobile and desktop devices. They need the info to be easily found and digested in a clear manner.

## Technical Capabilities

Using the bootstrap framework for this project allows changes to be made easily and efficiently. Some animations can be added at a later date for example a moving carouse instead of the static card-items showcasing the restaurants, as it was not within the scope at this time.

## Business Vision

The purpose of this project is to cater to both users with an active interest in food and cooking and those who are simply looking for a nice meal out with friends in Dublin. Partnerships could be struck with restaurants to feature their offers in the long-term. The same could be achieved as an end goal with food brands to feature their produce in the recipe of the week.

## Scope

For the audience I wanted to highlight the growing popularity of dining out in Dublin. This site could potentially be branched out to other cities around Ireland and Europe as a home page catering to millions of users looking for info about the city they live in or are visiting on a city-break.

## Structure

The structure of this site is laid out as a single homepage with separate sections denoted by the headings in the navbar. The site flows naturally, featuring an inviting image of Dublin from above, reminding the user what city is in question. From there, the user is invited to sign up to the newsletter which could contain info to entice users back again through email. This is completed with the use of a pop-up modal.

From there, the user can scroll to or select the Events link in the nabber which brings them to a section highlighting 3 restaurants with an offer that week. The pictures are clear and placed in a row of 3 which scales depending on device. Below the image is a description of the deal from the restaurant, followed by a clickable button which opens a new tab for the user to visit the restaurant’s homepage.

Following there, the user is greeted with 2 photos of a chef and a dish side by side and some text underneath giving a brief description of each.

The footer contains social icons hyperlinked to bring users to the facebook, instagram and twitter homepages respectively.

## Skeleton - Wireframes

See in images section for original vs updated wireframe 

## Features

Home: Main landing page with logo, navbar and slogan as well as modal button prompt to sign up to newsletter

Events: 3 featured events this week

Featured: A featured recipe and chef this week

Footer : contact us, map location and social links

Gallery = 4 photos.

## Implementation:

Due to this being my first project I ran into quite a few issues using bootstrap. I hand’t used chrome dev tools much and found it very useful to figure out padding, nested elements.

I also used it to play around with styling and colour schemes.

Testing usually went as follows:

Hard refresh using shift, ensure navbar worked, collapsed and expanded.

## Deployment

In my account GitHub website, I selected Repositories

I selected Hungrie-milestone1 from the GitHub Dashboard.

I navigated to Settings and to the GitHub Pages section.

From the Source section, I clicked on the drop-down menu and selected Master Branch.

Once Master Branch is selected, the page has been automatically refreshed, with a detailed ribbon display GitHub Source Saved Pages indicating the successful implementation.

I then decided to use a custom URL, so created a CNAME file with the URL www.travellingtainer.com as the domain, unfortunately there was an issue with the DNS settings and so this feature is one I intend on implementing in the near future.

The live link can be found here - https://damhanlk.github.io/hungrie-milestone1/

To run locally, you can clone this repository directly in your favorite editor, by typing in the terminal the following command:

git clone https://github.com/Damhanlk/hungrie-milestone1.git

How to run this project locally

To clone this project into Gitpod you will need:

A GitHub account. Create a GitHub account here : https://github.com/join?source=login Use the Chrome Browser

Then follow these steps:

Install the Gitpod browser extension for Chrome here: https://www.gitpod.io/docs/browser-extension After installation, restart the browser. Log into Gitpod with your Gitpod account. Navigate to the repository: https://github.com/Damhanlk/milestone1-hungr.ie

## Bugs

Initially for the project I wanted to have a slightly different landing page set up. The original thought was to have a blurred/less bright background image in order for the logo and hero text to pop against the background more. However the child elements kept inheriting the filter of the background image as they were nested within the same div. In future I will be sure to be mindful of child divs inheriting filter strengths, as at the time this was quite confusing, and in the end I decided to remove the brightness filter altogether, which I still think looks good for the end user.

I also originally had the hungr.ie logo which can be seen at the left of the Navbar and was created using Canva, also placed inside the hero section and aligned centrally. I encountered issues with scaling here as when moving to smaller screen sizes, the image either became cut off if widths and heights were clearly defined in CSS, or when I opted to try to scale the image, it became stretched and out of focus. I felt in the end that this detracted from the hero image and as such made the home page feel less welcoming and of a worse quality than a user would like to see on arrival to the site.

Originally the plan was to also make this page into 4 separate html docs which would open in separate tabs for the user. See wireframes. However using these locally was proving to be slightly cumbersome myself so for better and clearer UX I decided to go for the single page set up with nav elements directing to each.

The modal prompt to sign up to the newsletter I added using the bootstrap component library and after importing jquery. As Javascript was not within the scope of this project and outside of my knowledge I was struggling with the submit button and where it should lead when clicked. In the end I decided for it to lead to another html doc called thankyou.html. I’m not totally happy with this obviously and would prefer the user stay on the site itself and be displayed with a thank you message animated within the modal. This can be added at a later date.

There were some slight issues with GitPod at times, so Js.fiddle was used in order to run snippets of code. This was then pasted in. Due to this some commits were larger than I would have liked on the repository.

My gallery was buggy and unfortunately I couldn't get bootstrap to function here to fill the pictures to the screen in time.

I removed the hero-zoom on the hero image as it made the site quite slow.

## Testing

HMTL5 CSS3 Bootstrap v4.5.3 Google chrome dev tools - debugging query - for use of modal with bootstrap.

The website was tested both after the creation of each section separately but also after its completion. I tested all the functionality in the main browsers that ran on several operating systems: Chrome, Firefox, Safari, Windows 10, Mac OSX 10.14, and Android operating systems.

Testing during section construction was done primarily with Chrome DevTools, making sure each element works correctly and optimally, including responsiveness across devices. For navbar, I tested the functionality of all links, including the site brand. I also tested the color change of links to hover and toggle and collapse functioning in small devices.

During testing, I realised the Landing Text was causing responsiveness issues, which was easily fixed by inserting display:none; into the CSS of this heading.

I conducted several user tests to ensure there was an ease of use with this site, and all users reported the site was well functioning and user friendly. No users reported the Dog-Icon Navbar as an issue

When User stories are taken into account, testing ensured that ingormation was clearly visible and the site was easily navigable to new and returning users. Subscribing to the newsletter was straightforward, however I would have preferred more functionality there. 
## Credits

All of the images used on this site were taken from https://unsplash.com/

Photo by STIL on Unsplash

Photo by Eaters Collective on Unsplash

Photo by Joseph Gonzalez on Unsplash

Photo by Edgar Castrejon on Unsplash

Photo by Brooke Lark on Unsplash

font awesome was used for the icons https://fontawesome.com/

google fonts was used for the fonts for the project https://fonts.google.com/

bootstrap components library was used for the card formatting of the events page https://getbootstrap.com/docs/4.0/components/card/

and also for the modal https://getbootstrap.com/docs/4.0/components/modal/

readme format https://github.com/Code-Institute-Solutions/readme-template

## Acknowledgements :

Thanks you to the mentor and lead team who talked us through the readme and deployment process, and the code institute lecturers for the bootstrap bootcamp.

