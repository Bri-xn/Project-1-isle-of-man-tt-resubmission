# Isle of Man TT Website

<p>isle of man TT is a site towards bike enthusiast and people new and wanting to know more about the motorsport.
here they can find the history about the event,the track,the riders and a signup page for updates on the isle of man races</p>
[nav-screenshot](navagation.png)

## Features

### Header

- Universal Header across all pages
- Logo: "Isle of Man TT"
- Navigation Links: Home, The Racers, Newsletter

![title navagation](https://github.com/Bri-xn/Project-1-isle-of-man-tt-resubmission/assets/131008714/8a870141-c179-442c-b0a4-9456fec3ad5b)


### Main Section

#### About the Isle of Man TT

- Explanation of what the Isle of Man TT is.
- Image of a racer (Michael Dunlop) in action.
![title and description](https://github.com/Bri-xn/Project-1-isle-of-man-tt-resubmission/assets/131008714/7cd6558d-05be-4591-a7f1-3c9e94103be2)




#### Track Details

- Users can gather Information about the Snaefell Mountain Course.
- Image of the track map.
![track ](https://github.com/Bri-xn/Project-1-isle-of-man-tt-resubmission/assets/131008714/ca172c97-88d1-43de-b049-70c9c1389e2d)



### Video Section

- An embedded YouTube video related to the Isle of Man TT.

![youtube video](https://github.com/Bri-xn/Project-1-isle-of-man-tt-resubmission/assets/131008714/93eef478-cf9c-49af-b61d-c2b37539b518)

# Footer

![socials](https://github.com/Bri-xn/Project-1-isle-of-man-tt-resubmission/assets/131008714/43595870-737b-43a0-9131-2f4bb64e469c)

## Features

- **Social Media Links**: Direct links to the following social media platforms:
  - Facebook
  - Twitter
  - YouTube
  - Instagram
  
- **Font Awesome Icons**: The icons for each social media link are provided by Font Awesome.

## The Racers Page (`racers.html`)

### Overview

- The `racers.html` page is dedicated to showcasing profiles of some of the legendary racers who have participated in the Isle of Man TT races. This page contains biographies, images, and noteworthy facts about the racers.
#### Main Content

##### John McGuinness Section

- Profile of John McGuinness including an image and a small biography.

##### Micheal Dunlop Section

- Profile of Micheal Dunlop with a different layout including an image and a small biography.

##### Peter Hickman Section

- Profile of Peter Hickman including an image and a small biography.

![racers](https://github.com/Bri-xn/Project-1-isle-of-man-tt-resubmission/assets/131008714/39e0c46f-9393-454e-8bf8-172758d590e8)

## Newsletter Page (`signup.html`)

### Overview

The `signup.html` page is designed to encourage users to subscribe to the Isle of Man TT newsletter. The page contains a form for users to enter their first name, last name, and email address to subscribe to the newsletter. It maintains the visual theme and structure of other pages on the site.
![newsletter](https://github.com/Bri-xn/Project-1-isle-of-man-tt-resubmission/assets/131008714/e409b55e-dfb5-465c-85c9-5494e8660488)
##### Background Image

- The background image is set to cover the full viewport, giving the page a dynamic look.

##### Newsletter Subscription Form

- The form includes fields for users to enter their first name, last name, and email address.
- All fields are required for the subscription.
- Once submitted, the form redirects the user to a `thankyou.html` page.

## Thank You Page (`thankyou.html`)
![thank you](https://github.com/Bri-xn/Project-1-isle-of-man-tt-resubmission/assets/131008714/3f48e812-3752-4429-b897-4a14e49bc4da)


### Overview

The `thankyou.html` page is displayed to the users after they have successfully subscribed to the Isle of Man TT newsletter. This page confirms their successful subscription and thanks them for it. The page is simple, visually consistent with the rest of the site, and straightforward in its message.
##### Thank You Message

- The page features a large "Thank You for Signing Up!" heading, confirming the action the user took.
- A paragraph is included to elaborate on the success of the subscription.

## Bug Reporting and Common Issues
### Simple Class Errors

#### 1.1 Class Name Mismatch in CSS and HTML

- **Issue**: Classes defined in the CSS file are not taking effect in the HTML.
- **Possible Cause**: Class name mismatch between CSS and HTML files.
- **Solution**: Ensure that the class names in both the CSS and HTML files are consistent.

#### 1.2 Unstyled Elements

- **Issue**: Some HTML elements appear unstyled.
- **Possible Cause**: Forgotten to include class in HTML element.
- **Solution**: Include the appropriate class name in the HTML element.

#### 1.3 Overlapping Styles

- **Issue**: Styles from different classes overlap, causing styling issues.
- **Possible Cause**: Multiple classes applied to the same HTML element that contain conflicting styles.
- **Solution**: Resolve class conflict by modifying the CSS or restructuring the HTML elements.

---

### Syntax Errors

#### 2.1 Unclosed Tags

- **Issue**: Page layout breaks or certain elements do not display as expected.
- **Possible Cause**: HTML tags are not properly closed.
- **Solution**: Ensure all HTML tags are closed.

#### 2.2 Missing `;` in CSS

- **Issue**: Some styles are not applied.
- **Possible Cause**: Missing semicolon (`;`) at the end of CSS property.
- **Solution**: Add the missing semicolon in the CSS file.

#### 2.3 Invalid HTML Elements

- **Issue**: Browser console shows HTML validation errors.
- **Possible Cause**: Usage of invalid or deprecated HTML tags.
- **Solution**: Replace invalid tags with the correct HTML5 tags.
## Unfixed Bugs

### Media Queries

####  Responsive Layout Issues on Mobile

- **Issue**: The heading does not align properly on mobile screens.
- **Status**: Unresolved
- **Notes**: Although media queries are implemented to handle different screen sizes, the title and  layout breaks on mobile.
    I do apologize for this just could not figure out I tried everything out.

## Credits

### Image Credits

- All images used in this project are credited from google images
- The description of the racers and track were taken from chatGPT and Google 
- The sign up form i takenfrom love running ci templete.

- Embedded video was taken from here: (https://www.youtube.com/watch?v=vVG6VNlVlm4&t=1s&ab_channel=GastroRacing)


