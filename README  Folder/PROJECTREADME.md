# User-Centric-Front-End-Development-Milestone-Project
User Centric Front End Development Milestone Project

## Our World.

My project "Our World" hopes to inform the public on the natural world's current 
state, including climate change, deforesation, ocean pollution and air pollution. I decided to base my project on this 
for a few reasons, one being that I'm passionate about world preservation and helping
people see the good they can do with small changes to the way they lead their lives.

My project aim is to showcase what we are doing to our world. I will achieve this
through videos, pictures, and informative text. I also plan on having links to other,
real informative websites.

## UX
The website is directed at teens and adults. The idea is that these individuals wish to do better for our world. The website will enable this by giving them information under the "Make a Difference" tab that will allow them to see what changes they can make to help do less damage to the earth.

**An ideal viewer of this website would be someone that:**
* Doesn't recycle
* Drives a fuel-powered car
* Open-minded indivduals willing to change certain habits

**The viewer would be visiting my site if they are:**
* Looking to educate themselves on natural affairs
* Looking to make changes in their daily life to help the environment

**The website can help to achieve that because:**
* There are not enough websites that look to help educate an audience on this topic
* It's easily digestable information

The visitor should be able to navigate through the website with ease, regardless of which page or section they are on. It should be a seamless desktop-to-phone view, that allows for comfortable viewing on multiple devices. I want visitors to feel encouraged to contact the company if they wish to ask questions or discuss the natural affairs of our world. 

The website is not designed for returning clients. A visitor should leave the website feeling more solid with their knowledge on the topic and be then able to make changes to their lives if they see fit.

This website is not designed to produce any form of income, however it does have a donate option to allow people to put money toward various organisations. 

**Wireframes / Mockups Used:**

Here's the link to my first planning mockup: https://imgur.com/a/ZxeWJ1a

Here's the link to my second planning mockup:https://imgur.com/a/ZxeWJ1a.png

The mockups were very loosely followed. Even though it is not advised, I did improvise certain aspects as I saw fit. 

## Features

**Universal Website Features**

Header:
The header contains 4 links. The "Our World" title leads to Google Earth, as a quaint reference to what the website is about. The other links are "Who Are We?", "Make a Difference" and "Donate". The header collapses with screen width. 

Footer: 
The footer brings social links to the work, as well as a secondary navigation to allow ease of access after reaching the bottom of the page. Including a Contact tab as well, with a link that directly opens up a draft email to the ficitonal company. These footer features collapses into columns with width changes.

Newsletter:
The newsletter is a feature that would theoretically allow users to sign up for weekly, informative news. 

**The Home Page**

Callout:
The callout contains impact text and a youtube video discussing the catastrophic fires in the amazon rainforest. On mobile devices this video retains and is simply reduced in size. 

Gallery:
The gallery has some photos of the environment in peril, coupled with a box of brief information. When viewing this part of the website on a mobile device or tablet, the gallery shrinks, the text box disappears and an image carousel replaces the section. 

**The "Who Are We?" Page**

Google Maps:
I imbedded a Google Maps link to Canary Wharf, the location of the fictional offices for Our World. There is a text box beside this which discusses who the company are. When reducing the width, the map disappears and is replaced by an image of Canary Wharf's offices.

**The "Make a Difference" Page**

Information Boxes:
This page simply consists of some brief information on three different aspects of world health, partnered with some pictures. When the screen size is reduced, these boxes become a row as apposed to a column for mobile viewing ease.

**The "Donate" Page**

Donation Form:
The donation form is purely for visuals and as a user experience example. It consists of various inputs for name, surname, email and then the card details. I used "tel" to produce the desired formatting of my long card box. Coupled with a button to submit the form.

## Existing Features

* The "Our World" title feature allows the user to visit Google Earth by clicking the title.
* The Youtube video feature showcases major deforestation to the user by having them click play.
* The image slider feature, while only visible in mobile view, allows the user to see the gallery in a more refined, close space.
* The newsletter feature allows the user to sign up to the weekly newsletter by entering a valid email.
* The email feature Opens up the users mail and inputs Our World's hyopthetical email when clicking the button in the contact tab. 


## Features Left to Implement

- Even though the image slider is now functional, it does not have controls. At this moment in time, I do not possess enough knowledge to do this with just html / css. I believe further studies into javascript will help me achieve this goal.
- Possibly allowing the user to see a pinned location on google maps when hovering over a certain image.
- An interactive game about taking out trash for children, expanding the website's audience.
- I would have liked to make pop up bubbles for when the form or newsletter had been completed to notify the user.
- More control of the text outputted when not filling in the form correctly i.e giving it more context.
- The input for email to force the user to use a .com / .co.uk etc. instead of just the @ sign being enough to pass validation.

## Technologies Used

No languages were used in the coding of this project. It is pure HTML / CSS. No framworks or libraries were used. 

This website uses Google Fonts to style the website fonts.

https://fonts.google.com/specimen/Raleway?preview.text=OUR+WORLD&preview.text_type=custom

https://fonts.google.com/specimen/Noto+Sans+JP?preview.text=OUR+WORLD&preview.text_type=custom&query=Noto+Sans+JP

## Testing

During the time spent coding, I encountered various issues with my code. The most difficult one for me was figuring out how to correctly format and position parts of my website. I struggled to the content of my gallery where I wanted it. I originally had it all it div containers, which didn't allow for much customisation without the use of floats. I'm not a fan of using floats, so I did some research into flexbox. I experimented with it until I eventually was able to completely remove the old code I had and replace it with some new, refined flexbox code. This allowed me to have a much more flexible gallery that was even and precise. Customisation became easy and this solved one of my biggest issues with this project. I ran into a few, smaller issues along the way, however. 

I had an issue with embedding the video into my callout area. At first, I didn't use a youtube video. I had downloaded the video and implemented it locally. This proved difficult as I'm not yet experienced enough to create controls for that. On top of that, I couldn't get the width to adjust properly. So I left it for a couple days and decided to use a youtube video instead. After a few tutorials, I was able to figure out the width issue - and because it was an embedded video, I was able to have all the controls for quality, volume etc providing a more solid UX than my previous embedded video. 

Another issue, albeit a lot yes difficult to fix was an issue with my header. I wanted the navigation to sit underneath the the title instead of next to it. This however, was eventually solved with the help of Mr. Bim. The fix was simple, including the use of flex display and columns. 

#### User Experience Testing:

**Features on All Pages:**

1. The Title:
    1. Check that the title doesn't overlap the header contents when resizing.
    2. Verify that the title resizes as the width changes.
    3. Make sure that the title link to Google Earth is functional including the text changing colour when hovering over the title.

2. Navigation Bar:
    1. Go to home page.
    2. Change screen size to make sure the nav bar is funcitoning correctly in various widths, switching from a row to a column when changing widths.
    3. Verify that no words overlap or overflow when changing sizes when altering the screen size. 
    4. When hovering over any item in the navigation, the text should transition to a golden colour.
    5. Click the navigation links to make sure all links are working. 
    6. Make sure text becomes bold and is underlined when the user is on the corresponding page.
    7. Check that these links work properly and are easy to use when in tablet / mobile view.

3. Newsletter: 
    1. Check that the input field works correctly, only allowing the specific format to be inputted.
    2. Click the button with an empty input field to make sure you get an error.
    3. Resize screen to make sure the input field drops below the text at a certain width / mobile view.
    4. Check that in mobile view the input field remains functional.
    5. Verify that the text and input box do not overlap when being resized.

4. Footer Header:
    1. Change screen size to make sure the nav bar is funcitoning correctly in various widths, switching from a row to a column when changing widths.
    2. Verify that no words overlap or overflow in the different boxes when changing sizes when altering the screen size and become a column.
    3. When hovering over any item in the navigation, socials or contact tabs, the text should transition to a golden colour.
    4. Click the navigation links, socials links and email link to make sure all links are working. 
    5. Make sure text becomes bold and is underlined when the user is on the corresponding page.
    6. Check that these links work properly and are easy to use when in tablet / mobile view.
    7. Check that when resizing, the socials and contact tab don't overlap or overflow.
    8. Confirm that the socials tabs open in a new window.

**Home Page**

1. Callout Text / Video:
    1. Check that the imbedded video works, allowing users to watch the video when they please.
    2. Verify that all controls for the video work correctly.
    3. Check that youtube video and text resize correctly in various widths.
    4. Resize the page in both directions to make sure that the text / video do not overlap.

2. Gallery:
    1. Check to make sure all images resize correctly when changing size.
    2. Check that the text in the middle of the gallery moves correctly when resizing.
    3. When changing to mobile view, make sure the gallery turns into an image slider with a text bar beneath it.
    4. Resize back and fourth to verify that images and text don't overlap / overflow.

**"Who Are We?" Page**

1. Text Box and Google Maps:
    1. Check that the imbedded Google Maps box is working correctly and is showing Canary Wharf in London.
    2 Check to see if when resizing, the text box and google maps do not overlap / overflow.
    3. Make sure that at a certain width, the map dissapears and an image of Canary Wharf takes it place with a textbox beneath it.
    4. Verify that no text or images overlap when resizing to mobile view.

**"Make a Difference" Page**

1. Informative Boxes:
    1. All images and text boxes are lined up accordingly.
    2. Check to see if all images / text resize correctly when expanding or reducing the width of the page.
    3. Make sure that the three boxes become a column in mobile view.
    4. Verify that the text resizes when necessary, namely the Deforestation title as it is one word and does not break into seperate pieces like the other two titles.
    5. Confirm that the images remain central and retain the same width as each other when resizing.

**"Donate" Page:**

1. Donation Form:
    1. Try submitting an empty form and make sure an error appears.
    2. Try submitting a form with one incorrect box to verify that an error appears corresponding to which input had an error.
    3. Attempt to submit a form with all input fields filled out correctly for a successful form submission.
    4. Change the width of the screen size to make sure the form resizes correctly, with it's max width keeping it central and not oversized.
 
**Logical Testing for The Newsletter:**

IF the user clicks the "Subscribe" button without having typed anything the input box THEN give error message asking for an input.

IF the user does not include an @ sign in the input field and clicks the button THEN give error message asking for correct foramtting. 

IF the user enters a correctly formatted email into the input box and clicks button THEN the input passes validation and no errors occur.

**Logical Testing for The Donation Form:**

IF the user doesn't input the correct formatting for 1 of the fields despite having filled the rest of the form out correct and clicks the button THEN an error occurs asking the user to fill out the first input box that has conflicted with the formatting. 

IF the user inputs all information correctly into the input fields and clicks the "Make a Difference" button THEN the form will submit and be completed.

IF the user clicks the "Make a Difference" button without having inputted any information THEN aler the user to fill in the form.

IF the user types text into an input requesting a number input i.e Long Card Number and clicks the "Make a Difference" button THEN give an error asking for correct formatting. 

**Further Testing**
I asked my parents and sister to test the site, as well as my mentor and a friend on Slack.

- 

## Deployment
This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.

## Credits

https://www.rubicon.com/blog/ocean-pollution-facts/ - For the paragraph on Ocean Pollution.

https://www.conserve-energy-future.com/various-deforestation-facts.php - For the paragraph on Deforesation.


## Media Used:

Below are the links to the websites that I obtained all images from. 

https://www.offshore-technology.com/news/optical-remote-sensing-provides-ocean-oil-spill-data/

https://www.niehs.nih.gov/health/topics/agents/air-pollution/index.cfm

https://springpowerandgas.us/how-do-we-pollute-9-types-of-ocean-pollution/

https://www.inyourarea.co.uk/news/canary-wharf-tops-out-the-uks-tallest-residential-skyscraper-newfoundland-available-to-rent-in-2020/

https://www.plantbasednews.org/news/bali-bans-single-use-plastic

https://emerging-europe.com/news/air-pollution-may-have-adverse-effect-on-covid-19-patients-experts-warn/

https://www.rainforest-alliance.org/articles/relationship-between-deforestation-climate-change

https://www.elitereaders.com/damaged-nature/

https://www.abc.net.au/news/2019-10-30/melting-greenland-glaciers-weighed-by-australian-scientists/11630970

https://www.commondreams.org/news/2019/09/13/amazon-rainforest-burns-brazils-environment-minister-meet-us-group-denies-climate

https://en.wikipedia.org/wiki/Earth

https://www.nytimes.com/2020/01/13/science/air-pollution-fires-genes.html?smid=tw-nytimesworld&smtyp=cur

## Acknowledgements

I'd like to thank Mr. Bim in the Slack chat for helping me out when I would get stuck on something, such as the header navigation positionin.

Using the following video, I was able to understand and build an image slider.
https://www.youtube.com/watch?v=pGHOaY4dhAA&t=211s

