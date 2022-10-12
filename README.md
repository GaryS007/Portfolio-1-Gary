# Physio Medical

Physio Medical is a Website that enables people seeking assistance with physical pain to read information about that pain and also conveniently arrange an appointment. With a simple yet attractive homepage that will briefly explain what we do and how we can help. A treatments pain which anyone suffering with pain can relate to and read information about. Then finally a contact us page which allows them to contact the practice or look at their location via google maps. This website is specifically for people seeking a Physical Therapist in their local area so they can arrange an appointment and seek treatment ASAP.

The aim of my project was to build a functional, practical and responsive website using CSS and HTML.

![Responsive image of website](https://garys007.github.io/Portfolio-1-Gary/assets/images/readme-images/Responsive.png)

[Live link to website](https://garys007.github.io/Portfolio-1-Gary/)

## Features

### Social Media Header 

The first thing I built was the Social Media Header. I wanted to have the social media icons in the header and the footer for additional visibility. The header icons also include Phone & Email contact buttons for convenience. 

- Social Media Header is featured on all pages. Was created using a simple layout with hover effects.
- The only media query required is to ``text-align: center;``

### Navigation and Logo

![Navigation Screenshot](https://garys007.github.io/Portfolio-1-Gary/assets/images/readme-images/Navigation.png)

The mock design had different plans for the header, but changed my mind when it came to implementing the code. Due to having a small navigation, I liked the idea of centering the logo and navigation menus to make better use of space on more popular viewing devices.

- Logo & Navigation is present on all pages and is fully responsive.
- I used Flexbox for my header container to ensure responsiveness and to reduce the amount of media queries required.
- Navigation has a unique and stylish hover effect with a .5s transition set. This specific effect is only viewable on desktop devices.

### Home Page

![Homepage Grid Layout](https://garys007.github.io/Portfolio-1-Gary/assets/images/readme-images/Home-Grid.png)

I wanted a simple homepage design that can talk about how we as a Physical Therapist practice can help somebody in pain and to have the ability to link them to internal pages to provide them with additional assistance. I learned about CSS Grid and wanted to use CSS Grid on my home page to create achieve a responsive page with few media queries.

- Just like my mock I did a simple 4 box layout, Image Left, Text Right. Then on a new row, Text Left and Image Right. 
- Each text box has a H2 and a button to bring the visitor to the appropriate page.
- Full width hero image this hero image design is utilized on all internal pages.
- This section provides the user with nice imagery and quick understanding on the next steps of seeking treatment.

### Footer

![Footer](https://garys007.github.io/Portfolio-1-Gary/assets/images/readme-images/Footer.png)

- This section includes links to each relevant social media platform.
- Links open up in new tabs so the customer can easily navigate back to the website.
- Contact Information & Copyright information also present.
- Used a contrasting dark shade of grey to compliment the chosen design colour.

### Treatments

![Common Treatment Options](https://garys007.github.io/Portfolio-1-Gary/assets/images/readme-images/Common-Treatments.png)

The Treatments page enables the User to quickly choose what pain they are suffering with. It contains a short intro to the benefits of Physical Therapy and by clicking More Info on one of the pain types, it will anchor to the appropriate text which also has a Contact Us button so they can get in touch with the practice in relation to the pain they're experiencing. This functionality prevents excessive scrolling which is beneficial when on smaller mobile devices. They can access information required with the click of a button. Using anchors prevents the need for additional html pages.

- I used Flexbox to achieve this section, using flexbox reduces the amount of media queries required to make the content fit. I could have used Grid for this also, but wanted my Treatments page to fully utilize flexbox in all design choices.
- More Info will anchor directly to more text associated with the pain type to minimize the amount of scrolling required.
- Convenient and Flexible section that contains image, h2, text and call to action button with a grety background to make each section pop. 

![Individual Pain Types with Text](https://garys007.github.io/Portfolio-1-Gary/assets/images/readme-images/Pain-Types.png)

### Contact Us

![Contact Us Layout](https://garys007.github.io/Portfolio-1-Gary/assets/images/readme-images/Contact.png)

Simple contact page layout enabling the user to locate all contact details required, a contact us form to fill out or interact with the google map location.

- Flexbox to achieve a responsive design with minimal media queries.
- iframe from Google Maps for directions.
- Form to enable user to contact the company from the website directly.

### Features left to implement

- I would ideally directly connect a 3rd party piece of software to enable a user to book a specific timeslot for a treatment.
- Use Javascript to have a more feature rich Treatments page. Instead of using anchors, use Javascript to load in appropriate imagery/text for each specific treatment issue.

## Testing

While building this website, I created a Test Page to test new ideas and specific layouts. As a rule of thumb, I did a lot of my testing as I built each section. I didn't want to move on from 1 section to another until I was satisfied. Manually clicking and testing each URL, using Chrome Dev Tools to test responsiveness on all pages for each specific section. 

### Validator Testing
- Ran all **HTML** through [WC3 Validator](https://validator.w3.org/) and found some basic errors. 
    - Remove trailing slashes on void elements. 
    - Adding spaces to ``<a href=>`` resulted in errors. Removed spaces on all pages where appropriate.
    - he first child option element of a select element with a required attribute, and without a multiple attribute, and without a size attribute whose value is greater than 1, must have either an empty value attribute, or must have no text content. Consider either adding a placeholder option label, or adding a size attribute with a value equal to the number of option elements. **As a result of this error, I added in ``<option hidden value>--Choose One--</option>`` to resolve it**
    - Rename all imagery to remove spaces from file names.
    - Incorrect indentation resulted in some display issues.
    
### Unfixed Bugs

All bugs have been resolved. There are some concepts I would have liked to implement or test using Javascript. Specifically on the Treatments page, instead of relying on Anchors to each piece of content, I could use Javascript to load in the necessary Text/Imagery when the user clicked on More Info. This would reduce scrolling and be a bit more slick. It could have also allowed me to add more text to each pain type.

I wasn't 100% happy with the Imagery, I think for more business orientated websites paying a subscription to the likes of shutterstock would be worthwhile as they provide far superior images.

## Deployment
 
- The site was deployed to GitHub pages. The steps to deploy are as follows:
    - In the GitHub repository, navigate to the Settings tab
    - From the source section drop-down menu, select the Master Branch
    - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

    The live link can be found here - https://garys007.github.io/Portfolio-1-Gary/index.html

## Credits

- Treatments Page Text was taken directly from Wikipedia, you can view each article I used here - [Neck Pain](https://en.wikipedia.org/wiki/Neck_pain) | [Back Pain](https://en.wikipedia.org/wiki/Back_pain) | [Chronic Pain](https://en.wikipedia.org/wiki/Chronic_pain) | [Sports Injury](https://en.wikipedia.org/wiki/Sports_injury) | [Shoulder Problems](https://en.wikipedia.org/wiki/Shoulder_problem) | [Running Injuries](https://en.wikipedia.org/wiki/Running_injuries)
- I learned how to implement Grid and Flexbox via Youtube Tutorials. The channel is by Kevin Powell and here are the 2 videos I focused on - [Learn Grid the Easy Way CSS](https://www.youtube.com/watch?v=rg7Fvvl3taU&t=3s&ab_channel=KevinPowell) | [Learn Flexbox the easy way CSS](https://www.youtube.com/watch?v=u044iM9xsWU&ab_channel=KevinPowell)
- All Images were sourced from Pixabay and Pexels. 
- Logo was designed by a family member for my website specifically.

## Mock Designs

I did a Homepage Mock and a Treatments page Mock as these were the 2 most important layouts to me. I did end up deviating from the original design a little bit. Only when I seen my mock live, did I realise I wanted to amend some things.

![Homepage Mock](https://garys007.github.io/Portfolio-1-Gary/assets/images/readme-images/Homepage-Mock.png)

![Treatments Mock](https://garys007.github.io/Portfolio-1-Gary/assets/images/readme-images/Treatments-Mock.png)


