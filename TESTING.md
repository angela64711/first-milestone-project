# Testing

> [!NOTE]  
> Return back to the [README.md](README.md) file.

## Code Validation

### HTML

I have used the recommended [HTML W3C Validator](https://validator.w3.org) to validate all of my HTML files.

| Directory | File | URL | Screenshot | Notes |
| --- | --- | --- | --- | --- |
|  | [404.html](https://github.com/angela64711/first-milestone-project/blob/main/404.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://angela64711.github.io/first-milestone-project/404.html) | ![screenshot](documentation/validation/html--404.png) 
|  | [about.html](https://github.com/angela64711/first-milestone-project/blob/main/about.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://angela64711.github.io/first-milestone-project/about.html) | ![screenshot](documentation/validation/html--about.png) | 
|  | [contact.html](https://github.com/angela64711/first-milestone-project/blob/main/contact.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://angela64711.github.io/first-milestone-project/contact.html) | ![screenshot](documentation/validation/html--contact.png) | 
|  | [index.html](https://github.com/angela64711/first-milestone-project/blob/main/index.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://angela64711.github.io/first-milestone-project/index.html) | ![screenshot](documentation/validation/html--index.png) | 
|  | [services.html](https://github.com/angela64711/first-milestone-project/blob/main/services.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://angela64711.github.io/first-milestone-project/services.html) | ![screenshot](documentation/validation/html--services.png) | 
|  | [success.html](https://github.com/angela64711/first-milestone-project/blob/main/success.html) | [HTML Validator](https://validator.w3.org/nu/?doc=https://angela64711.github.io/first-milestone-project/success.html) | ![screenshot](documentation/validation/html--success.png) | 


### CSS

I have used the recommended [CSS Jigsaw Validator](https://jigsaw.w3.org/css-validator) to validate all of my CSS files.

| Directory | File | URL | Screenshot | Notes |
| --- | --- | --- | --- | --- |
| assets | [style.css](https://github.com/angela64711/first-milestone-project/blob/main/assets/css/style.css) | [CSS Validator](https://jigsaw.w3.org/css-validator/validator?uri=https://angela64711.github.io/first-milestone-project) | ![screenshot](documentation/validation/css-assets-style.png) | 


## Responsiveness

I've tested my deployed project to check for responsiveness issues.

| Page | Mobile | Tablet | Desktop | Notes |
| --- | --- | --- | --- | --- |
| Home | ![screenshot](documentation/responsiveness/mobile-home.png) | ![screenshot](documentation/responsiveness/tablet-home.png) | ![screenshot](documentation/responsiveness/desktop-home.png) | Works as expected |
| Services | ![screenshot](documentation/responsiveness/mobile-services.png) | ![screenshot](documentation/responsiveness/tablet-services.png) | ![screenshot](documentation/responsiveness/desktop-services.png) | Works as expected |
| About Me | ![screenshot](documentation/responsiveness/mobile-about.png) | ![screenshot](documentation/responsiveness/tablet-about.png) | ![screenshot](documentation/responsiveness/desktop-about.png) | Works as expected |
| Contact | ![screenshot](documentation/responsiveness/mobile-contact.png) | ![screenshot](documentation/responsiveness/tablet-contact.png) | ![screenshot](documentation/responsiveness/desktop-contact.png) | Works as expected |
| Success | ![screenshot](documentation/responsiveness/mobile-success.png) | ![screenshot](documentation/responsiveness/tablet-success.png) | ![screenshot](documentation/responsiveness/desktop-success.png) | Works as expected |
| 404 | ![screenshot](documentation/responsiveness/mobile-404.png) | ![screenshot](documentation/responsiveness/tablet-404.png) | ![screenshot](documentation/responsiveness/desktop-404.png) | Works as expected |

## Browser Compatibility

I've tested my deployed project on multiple browsers to check for compatibility issues.

| Page | Chrome | Firefox | Edge | Notes |
| --- | --- | --- | --- | --- |
| Home | ![screenshot](documentation/testing/chrome-home.png) | ![screenshot](documentation/testing/firefox-home.png) | ![screenshot](documentation/testing/edge-home.webp) | Works as expected |
| Services | ![screenshot](documentation/testing/chrome-services.png) | ![screenshot](documentation/testing/firefox-services.png) | ![screenshot](documentation/testing/edge-services.webp) | Works as expected |
| About Me | ![screenshot](documentation/testing/chrome-about.png) | ![screenshot](documentation/testing/firefox-about.png) | ![screenshot](documentation/testing/edge-about.webp) | Works as expected |
| Contact | ![screenshot](documentation/testing/chrome-contact.png) | ![screenshot](documentation/testing/firefox-contact.png) | ![screenshot](documentation/testing/edge-contact.webp) | Works as expected |
| Success | ![screenshot](documentation/testing/chrome-success.png) | ![screenshot](documentation/testing/firefox-success.png) | ![screenshot](documentation/testing/edge-success.webp) | Works as expected |
| 404 | ![screenshot](documentation/testing/chrome-404.png) | ![screenshot](documentation/testing/firefox-404.png) | ![screenshot](documentation/testing/edge-404.webp) | Works as expected |

## Lighthouse Audit

I've tested my deployed project using the Lighthouse Audit tool to check for any major issues. Some warnings are outside of my control, and mobile results tend to be lower than desktop.

| Page | Mobile | Desktop |
| --- | --- | --- |
| Home | ![screenshot](documentation/lighthouse/mobile-home.png) | ![screenshot](documentation/lighthouse/desktop-home.png) |
| Services | ![screenshot](documentation/lighthouse/mobile-services.png) | ![screenshot](documentation/lighthouse/desktop-services.png) |
| About Me | ![screenshot](documentation/lighthouse/mobile-about.png) | ![screenshot](documentation/lighthouse/desktop-about.png) |
| Contact | ![screenshot](documentation/lighthouse/mobile-contact.png) | ![screenshot](documentation/lighthouse/desktop-contact.png) |
| Success | ![screenshot](documentation/lighthouse/mobile-success.png) | ![screenshot](documentation/lighthouse/desktop-success.png) |
| 404 | ![screenshot](documentation/lighthouse/mobile-404.png) | ![screenshot](documentation/lighthouse/desktop-404.png) |

## Defensive Programming

Defensive programming was manually tested with the below user acceptance testing:

| Page | Expectation | Test | Result | Screenshot | Screenshot 2 |
| --- | --- |  --- |  --- |  --- |
| | Feature is expected to have accessible navigation links. | Checked navigation links for correct functionality and accessibility. | Navigation links were functional and accessible. | ![screenshot](documentation/defensive/navigation.png) |
| | Feature is expected to be fully responsive. | Resized the browser window and tested on multiple devices (mobile, tablet, desktop). | The page was responsive across all tested screen sizes. | ![screenshot](documentation/defensive/responsive01.png) | ![screenshot](documentation/defensive/responsive02.png) |
| Home | Feature is expected to display a hero image with the doula's name, a desciption of what she doeas and her moto, along with a CTA to contact her. | Verified that the page displays the doula's name, field and moto in a clear and concise manner. | The CTA to the contact page works as expected. | ![screenshot](documentation/defensive/hero.png) 
| Home | Feature is expected to display four cards, summarizing each of the services offered. Each is expected to inclide a link to the corresponding section in the srvices page.| Verified that the cards are displayed as expected | The links to the services page works as expected. | ![screenshot](documentation/defensive/cards.png) | ![screenshot](documentation/defensive/card-link.png) |
| Home | Feature is expected to display a portrait image of the doula, a short text about her, along with a CTA to find out more about her, which links to the About Me page. | Verified that the page displays the doula's portrait and a short text. | The CTA to the About Me page works as expected. | ![screenshot](documentation/defensive/doula01.png) |
| Home | Feature is expected to display two logos of the websites where the doula has been featured, both of which are links to the corresponding websites. | Verified that the page displays the featured in section with the two logos. | The links to the websites work as expected and open in a different tab. | ![screenshot](documentation/defensive/featured.png) | ![screenshot](documentation/defensive/tcm.png) |
| Services | Feature is expected to show the services the doula offers, after a short intro text,  along with detailed descriptions of what they include, an image and a CTA to the contact page | Confirmed that the page displays the services, ina structured manner. | Each link to the contact page works as expected. | ![screenshot](documentation/defensive/services.png) | ![screenshot](documentation/defensive/services.png) |
| Services | Feature is expected to show the packages the doula offers along with their prices. | Confirmed that the page contains the four packages offered. | They was displayed as expected. | ![screenshot](documentation/defensive/packages.png) |
| About Me | Feature is expected to show a portrait picture of the doula, a short intro about her with a CTA to send a message, allong with a long text about her story and a CTA to the services page. | Confirmed that the page contains the portrait image of the doula, along with the two texts and two CTA buttons. | The links work as expected. | ![screenshot](documentation/defensive/about.png) |
| About Me | Feature is expected to show the doula's education, credentials and training in the form of a list. | Confirmed that the page contains all the necessary information about her qualifications. | All the credentials were displayed as expected. | ![screenshot](documentation/defensive/schedule.png) |
| Contact | Feature is expected to prevent submission of an empty form. | Attempted to submit the form without filling any fields. | Form submission was blocked, as expected. | ![screenshot](documentation/defensive/contact01.png) |
| Contact | Feature is expected to enforce valid input types for each field. | Entered invalid data (e.g., random text in an email field, numbers in a name field, etc.). | Error messages were displayed appropriately, and submission was blocked. | ![screenshot](documentation/defensive/contact02.png) |
| Success | Feature is expected to show an affirmative message after the form has been submited correctly, which includes a link to the home page. | Entered valid data. | Success messages were displayed appropriately and the link worked as expected. | ![screenshot](documentation/defensive/success.png) |
| Social Links | Feature is expected to include working links to the doula’s social platforms (Instagram and Facebook). | Clicked each social link to verify redirection to the correct platform page. | All links redirected to the correct platform pages, opening in new browser tabs. | ![screenshot](documentation/defensive/facebook.png) | ![screenshot](documentation/defensive/instagram.png)
| 404 Error Page | Feature is expected to display a 404 error page for non-existent pages. | Navigated to an invalid URL (e.g., `/no`) to test error handling. | A custom 404 error page was displayed as expected. | ![screenshot](documentation/defensive/404.png) |

## User Story Testing

⚠️ INSTRUCTIONS ⚠️

Testing User Stories is actually quite simple, once you've already got the stories defined on your README.

Most of your project's **Features** should already align with the **User Stories**, so this should be as simple as creating a table with the User Story, matching with the re-used screenshot from the respective Feature.

⚠️ --- END --- ⚠️

| Target | Expectation | Outcome | Screenshot | 
| --- | --- | --- | --- | 
| As a user | I would like to see examples of why I should join | so that I can learn about the club’s mission and purpose before deciding to join. | ![screenshot](documentation/features/feature01.png) |
| As a user | I would like to view the running schedule/timetable | so that I can decide when to join a session. | ![screenshot](documentation/features/feature02.png) |
| As a user | I would like to see the details of different running events | so that I can prepare accordingly. | ![screenshot](documentation/features/feature03.png) |
| As a user | I would like to view a gallery of past events | so that I can see photos of myself and others from previous runs. | ![screenshot](documentation/features/feature04.png) |
| As a user | I would like to sign up for the running club | so that I can join the community and participate in events. | ![screenshot](documentation/features/feature05.png) |
| As a user | I would like to follow the club on various platforms (e.g., Instagram, Facebook, Twitter) | so that I can stay updated with club news and events. | ![screenshot](documentation/features/feature06.png) |
| As a user | I would like the website to be fully responsive | so that I can easily navigate and access information from my phone, tablet, or desktop. | ![screenshot](documentation/features/feature07.png) |
| As a user | I would like to see a 404 error page if I get lost | so that it's obvious that I've stumbled upon a page that doesn't exist. | ![screenshot](documentation/features/feature08.png) |

## Bugs

⚠️ INSTRUCTIONS ⚠️

Nobody likes bugs,... except the assessors! Projects seem more suspicious if a student doesn't properly track their bugs. If you're about to submit your project without any bugs listed below, you should ask yourself why you're doing this course in the first place, if you're able to build this entire application without running into any bugs. The best thing you can do for any project is to document your bugs! Not only does it show the true stages of development, but think of it as breadcrumbs for yourself in the future, should you encounter the same/similar bug again, it acts as a gentle reminder on what you did to fix the bug.

If/when you encounter bugs during the development stages of your project, you should document them here, ideally with a screenshot explaining what the issue was, and what you did to fix the bug.

Alternatively, an improved way to manage bugs is to use the built-in **[Issues](https://www.github.com/angela64711/first-milestone-project/issues)** tracker on your GitHub repository. This can be found at the top of your repository, the tab called "Issues".

If using the Issues tracker for bug management, you can simplify the documentation process for testing. Issues allow you to directly paste screenshots into the issue page without having to first save the screenshot locally. You can add labels to your issues (e.g. `bug`), assign yourself as the owner, and add comments/updates as you progress with fixing the issue(s). Once you've solved the issue/bug, you should then "Close" it.

When showcasing your bug tracking for assessment, you can use the following examples below.

⚠️ --- END --- ⚠️

### Fixed Bugs

[![GitHub issue custom search](https://img.shields.io/github/issues-search/angela64711/first-milestone-project?query=is%3Aissue%20is%3Aclosed%20label%3Abug&label=Fixed%20Bugs&color=green)](https://www.github.com/angela64711/first-milestone-project/issues?q=is%3Aissue+is%3Aclosed+label%3Abug)

I've used [GitHub Issues](https://www.github.com/angela64711/first-milestone-project/issues) to track and manage bugs and issues during the development stages of my project.

All previously closed/fixed bugs can be tracked [here](https://www.github.com/angela64711/first-milestone-project/issues?q=is%3Aissue+is%3Aclosed+label%3Abug).

![screenshot](documentation/bugs/gh-issues-closed.png)

### Unfixed Bugs

⚠️ INSTRUCTIONS ⚠️

You will need to mention any unfixed bugs and why they are not fixed upon submission of your project. This section should include shortcomings of the frameworks or technologies used. Although time can be a big variable to consider, paucity of time and difficulty understanding implementation is not a valid reason to leave bugs unfixed. Where possible, you must fix all outstanding bugs, unless outside of your control.

If you've identified any unfixed bugs, no matter how small, be sure to list them here! It's better to be honest and list them, because if it's not documented and an assessor finds the issue, they need to know whether or not you're aware of them as well, and why you've not corrected/fixed them.

⚠️ --- END --- ⚠️

[![GitHub issue custom search](https://img.shields.io/github/issues-search/angela64711/first-milestone-project?query=is%3Aissue%2Bis%3Aopen%2Blabel%3Abug&label=Unfixed%20Bugs&color=red)](https://www.github.com/angela64711/first-milestone-project/issues?q=is%3Aissue+is%3Aopen+label%3Abug)

Any remaining open issues can be tracked [here](https://www.github.com/angela64711/first-milestone-project/issues?q=is%3Aissue+is%3Aopen+label%3Abug).

![screenshot](documentation/bugs/gh-issues-open.png)

NOTE: Service card buttons misalign slightly at some specific screen sizes, like 1500px and 1929px due to text reflow.
  They function well at Bootstrap breakpoints.
   Fix later with flex-based card layout if needed. 

### Known Issues

| Issue | Screenshot |
| --- | --- |
| The project is designed to be responsive from `375px` and upwards, in line with the material taught on the course LMS. Minor layout inconsistencies may occur on extra-wide (e.g. 4k/8k monitors), or smart-display devices (e.g. Nest Hub, Smart Watches, Gameboy Color, etc.), as these resolutions are outside the project’s scope, as taught by Code Institute. | ![screenshot](documentation/issues/poor-responsiveness.png) |
| When validating HTML with a semantic `<section>` element, the validator warns about lacking a header `h2-h6`. This is acceptable. | ![screenshot](documentation/issues/section-header.png) |

> [!IMPORTANT]  
> There are no remaining bugs that I am aware of, though, even after thorough testing, I cannot rule out the possibility.

