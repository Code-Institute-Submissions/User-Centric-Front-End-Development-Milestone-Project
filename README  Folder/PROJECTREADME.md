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

JQuery
The project uses JQuery to simplify DOM manipulation.

## Testing

During the time spent coding, I encountered various issues with my code. The most difficult one for me was figuring out how to correctly format and position parts of my website. I struggled to the content of my gallery where I wanted it. I originally had it all it div containers, which didn't allow for much customisation without the use of floats. I'm not a fan of using floats, so I did some research into flexbox. I experimented with it until I eventually was able to completely remove the old code I had and replace it with some new, refined flexbox code. This allowed me to have a much more flexible gallery that was even and precise. Customisation became easy and this solved one of my biggest issues with this project. I ran into a few, smaller issues along the way, however. 

I had an issue with embedding the video into my callout area. At first, I didn't use a youtube video. I had downloaded the video and implemented it locally. This proved difficult as I'm not yet experienced enough to create controls for that. On top of that, I couldn't get the width to adjust properly. So I left it for a couple days and decided to use a youtube video instead. After a few tutorials, I was able to figure out the width issue - and because it was an embedded video, I was able to have all the controls for quality, volume etc providing a more solid UX than my previous embedded video. 

Another issue, albeit a lot yes difficult to fix was an issue with my header. I wanted the navigation to sit underneath the the title instead of next to it. This however, was eventually solved with the help of Mr. Bim. The fix was simple, including the use of flex display and columns. 

#### User Experience Testing:

**Home Page:**

Navigation: 

UX for The Newsletter:

IF the user clicks the "Subscribe" button without having typed anything the input box THEN give error message asking for an input.

IF the user does not include an @ sign in the input field and clicks the button THEN give error message asking for correct foramtting. 

IF the user enters a correctly formatted email into the input box and clicks button THEN the input passes validation and no errors occur.

UX for The Donation Form:

IF the user doesn't input the correct formatting for 1 of the fields despite having filled the rest of the form out correct and clicks the button THEN an error occurs asking the user to fill out the first input box that has conflicted with the formatting. 

IF the user inputs all information correctly into the input fields and clicks the "Make a Difference" button THEN the form will submit and be completed.

IF the user clicks the "Make a Difference" button without having inputted any information THEN aler the user to fill in the form.

IF the user types text into an input requesting a number input i.e Long Card Number and clicks the "Make a Difference" button THEN give an error asking for correct formatting. 

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



Google Fonts:
https://fonts.google.com/specimen/Raleway?preview.text=OUR+WORLD&preview.text_type=custom

https://fonts.google.com/specimen/Noto+Sans+JP?preview.text=OUR+WORLD&preview.text_type=custom&query=Noto+Sans+JP

## Acknowledgements

I'd like to thank Mr. Bim in the Slack chat for helping me when I was stuck.

Using the following video, I was able to understand and build an image slider.
https://www.youtube.com/watch?v=pGHOaY4dhAA&t=211s

