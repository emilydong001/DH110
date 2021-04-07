# Accessible Delivery of Health & Healthcare Information to Seniors

## Assignment 1: Heuristic Evaluation

Emily Dong | DH110 | Spring 2021

### About the project

According to the United Nations, the number of seniors (65+) is expected to double to 1.5 billion by 2050 globally. Despite seniors being one of the fastest-growing and wealthiest demographics in wealthy countries, many digital products fail to meet senior accessibility needs and have made them feel excluded from an online world that is unfriendly to those with bad eyesight, declined dexterity, and unfamiliarity with the web. In particular, health is a major concern among seniors, and we should ensure that information is accessible to them. For this project, I hope to demonstrate how we can improve user (patient) experiences on websites with health, healthcare, and patient information so that seniors can maintain their well-being. Additionally, by designing for their accessibility, we are designing for everyone's accessibility.

### Jakob Nielson's [10 Usability Heuristics](https://www.nngroup.com/articles/ten-usability-heuristics/) Explained

| Number | Heuristic | Description |
|---|---|---|
| 1 | Visibility of System Status | Users should always be informed about what is going on and should be given appropriate feedback to their actions |
| 2 | Match Between System and the Real World | Use concepts and language that are familiar and logical to the user |
| 3 | User Control and Freedom | Allow users to make mistakes; give them options to undo and redo tasks |
| 4 | Consistency and Standards | Follow conventions and make sure design is consistent across the platform |
| 5 | Error Prevention | Get rid of error-prone conditions and provide users with safety nets for high-cost errors |
| 6 | Recognition Rather Than Recall | Minimize user's memory load by giving them suggestions and help in context |
| 7 | Flexibility and Efficiency of Use | Provide multiple ways to perform a task to make the platform accessible to all users |
| 8 | Aesthetic and Minimalist Design | Provide only relevant content and features |
| 9 | Help Users Recognize, Diagnose, and Recover From Errors | Tell users what the problem is and provide suggestions to fix it |
| 10 | Help and Documentation | Supply users with extra help to complete their tasks |


### [Severity Ratings](https://www.nngroup.com/articles/how-to-rate-the-severity-of-usability-problems/) for Usability Problems by Nielsen Norman Group

The following rating scale can be used to evaluate the severity of usability issues:
| Rating | Description |
|---|---|
| 1 | Cosmetic problem only: need not be fixed unless extra time is available on project |
| 2 | Minor usability problem: fixing this should be given low priority |
| 3 | Major usability problem: important to fix, so should be given high priority |

Ratings are displayed in parentheses after each usability issue.

## Website 1: [Mayo Clinic](https://www.mayoclinic.org/)

### About
[Mayo Clinic](https://www.mayoclinic.org/) is a non-profit American medical organization dedicated to clinical practice, education, and research, and whose location in Minnesota has been recognized as the best hospital of 2020-2021 by U.S. News & World Report. Mayo Clinic is a trusted source of medical information about diseases and conditions, possible causes for symptoms, drugs and supplements, tests and procedures, and healthy living.

The richness of health information and breadth of features on the Mayo Clinic website can be both valuable and overwhelming. My goal is to preserve the value while streamlining the user's ability to navigate throughout the website.

### Heuristic Evaluation

#### 1. Visibility of System Status
* As you type in the search bar, possible options are not immediately displayed, which makes it difficult for the user to understand how the system is responding to their query (results start displaying only after 3 letters are inputted, but users expect it to be instantaneous). Furthermore, the recommended results shown are sometimes almost completely unrelated to health or medical information, which doesn't help the user. (2)

<p align="center">
  <img src="../Images/search-query-2.PNG" alt="Search query no immediate results" width = "300px"/>
  <img src="../Images/search-query.png" alt="Search query irrelevant results" width = "300px"/>
</p>

> *Recommendation: Display results as the user types so that the user stays engaged, making it more likely they will continue to explore the site to find the information they need. Optimize search results so that they are relevant to health and medical information.*

* Within each major step in the appointment-making process, there are a bunch of other steps. Because there is little visual representation of progress, users could be thwarted by the number of times they have to click "Continue". There is an outline on the left that changes color for the *major* steps completed, but at the beginning of each major step, the whole screen turns blue, making the contrast too low to see their progress (1):

<p align="center">
  <img src="../Images/appointment-request-progress.PNG" alt="Appointment request progress capture" height = "300px"/>
</p>

* There is also a percentage completed shown at the top left as the total progress indicator, but it is so small that users probably wouldn't notice it at first glance. (1)
![Appointment Request Progress Capture](../Images/appointment-request-progress-2.PNG)

> *Recommendation: Don't make the whole page blue at each major step; keep the page gray/white to ensure contrast in the progress tracker. Also, create a visual representation of progress by numbering the steps and including arrows. Implement a progress bar that slides forward as the user completes the information.*

#### 2. Match Between System and the Real World
* Although it's not a big issue, the placeholder text of the search bar is "Search Mayo Clinic", which seems like a missed opportunity to guide users in the right direction or express something about the brand, especially since this is a very large website. (1)

<p align="center">
  <img src="../Images/search-bar.PNG" alt="Homepage search bar" width = "300px"/>
</p>

> *Recommendation: Consider modifying the placeholder text based on what would be most helpful for users' existing habits. Perhaps something like 'Search health topics, conditions, doctors' or whatever is most relevant to most users.*

#### 3. User Control and Freedom
* After searching for something in the search bar, the user's query is erased. If the user doesn't find the information they were looking for, which could happen often (especially since the recommended results don't immediately appear and may be irrelevant), they have to retype their query all over again. (2)

> *Recommendation: Don't erase the user's query after they hit Search so that they can slightly modify their query if necessary.*

#### 4. Consistency and Standards
* Their page for COVID-19 and vaccine information is completely different from their normal website, which could confuse users because it seems like a separate website. Also, the navigation is hidden in a hamburger menu on the top-right, which is both less discoverable and unconventional. (3)

<p align="center">
  <img src="../Images/homepage.PNG" alt="Mayo Clinic homepage"/>
  <img src="../Images/covid-19-page.PNG" alt="Mayo Clinic COVID-19 page"/>
</p>

> *Recommendation: Maintain consistency with the main website so that users understand they are still in the same space. Show navigation at the top rather than hiding it in the hamburger menu.*

* When you click Request Appointment, you cannot go back to the homepage by clicking the logo on the top-left corner, which can be frustrating for many users who expect that they can orient to the homepage by clicking the logo. I observed the same pattern across random pages of the website (including the Trouble Signing Up? page for account creation). The logo at the top left corner is probably the most common design pattern and needs to be upheld throughout the website. (3)

> *Recommendation: Make sure that clicking the logo will go back to the homepage on every page. In general, make sure every functionality is consistent throughout the website so that users don't get 'lost' on a certain page.*

#### 5. Error Prevention
* Mayo Clinic is currently not accepting online requests for COVID-19 vaccine appointments. Although they provide a warning message above the button to request an appointment, users can easily skip this message. In the following modal window, users would likely randomly click "Yes" or "No" without regard to what the message is because they are habituated to getting out of the dialog window as fast as possible. (3)

<p align="center">
  <img src="../Images/appointment-modal-window.PNG" alt="Modal window asking about COVID-19 vaccine" width="700px"/>
</p>

> *Recommendation: Get rid of the modal window and provide radio buttons to get users to make a deliberate choice between "Yes" and "No". It would also be helpful to display the error message again if the user clicks "Yes" rather than force them onto a page that doesn't explain the error they made.*

#### 6. Recognition Rather Than Recall
* On the health information page, the user must search by first letter (A-Z). This makes it difficult for users who may not know or remember the name of the disease or condition to access information about it. (2)

<p align="center">
  <img src="../Images/diseases-and-conditions.PNG" alt="Diseases and conditions page" width="500px"/>
</p>

> *Recommendation: Guide users to the symptom checker, where they can select from a list of symptoms and generate predicted diseases and conditions associated with those symptoms. In general, Mayo Clinic should better emphasize their symptom checker feature because it can be a great resource for those concerned with their health, like many seniors. (However, emphasize that it is necessary to check with a healthcare provider.)*

#### 7. Flexibility and Efficiency of Use
* Because the magnifying glass is within the search box, the user may not recognize that there is another way to trigger the search action (other than Enter). (1)

![Homepage of Mayo Clinic showing search box](../Images/homepage.PNG)

> *Recommendation: Create a separate button for searching that includes the magnifying glass so that the user easily recognizes that it can be clicked to Search.*

* On the symptom checker, the user needs to select from a large list of symptoms, which is cumbersome and overwhelming. (3)
![Symptom Checker Step 1 Capture](../Images/symptom-checker-step-1.PNG)

> *Recommendation: Keep the list so that users can just recognize and click on recommendations, but implement a search feature at the top so that users can have the option to efficiently find the symptom they are experiencing. Also, group the symptoms into different categories to help users find the symptom they are looking for more easily.*

* Under Billing, clicking the name of a category doesn't display the drop-down menu, but rather takes you to another page, which can be disorienting. The user must click the + sign to the right of the name to get the drop-down menu, which also requires dexterity and is therefore less accessible for seniors. (3)

> *Recommendation: Make it possible to access the drop-down by clicking the name of the category.*

#### 8. Aesthetic and Minimalist Design
* Because Mayo Clinic's website is very large, it can be difficult to consolidate all the information while ensuring the website is usable. However, there are some unnecessary elements that visually clutter the website. For instance, in the first dropdown of the navigation menu, there are many different links that are somewhat unnecessary - Clinical Trials is already under "Research" (it also makes more sense there), and "Digital Health Care" is almost the same thing as "Patient Online Services" to users (they only need to include one of these). (3)

<p align="center">
  <img src="../Images/nav-care-at-mayo-clinic.PNG" alt="Navigation menu (Care at Mayo Clinic)" width="250px"/>
  <img src="../Images/nav-research.PNG" alt="Navigation menu (Care at Mayo Clinic)" width="250px"/>
</p>

> *Recommendation: Show only what is necessary in the navigation menu, and make sure the links are relevant to each category.*

* The billing and payments page has a very cluttered and unappealing design, placing a lot of cognitive strain on the user. (3)

![Billing and payments page](../Images/billing-and-payments.PNG)

> *Recommendation: Clean up the page by putting more spacing between the words, using better hierarchy to organize the information, listing items out in bullet points rather than in paragraph form, and using more relevant and high-quality images for each category.*

* Lastly, the font size on the homepage navigation (and in other random locations throughout the website is small and faint, making it inaccessible for individuals with visual impairments. (3)

> *Recommendation: Increase font sizes and increase contrast of the fonts (in this case, make them darker) to make them readable for seniors and other visually impaired individuals. Create a design guideline to ensure that all font sizes and styles are consistent throughout the website.*

#### 9. Help Users Recognize, Diagnose, and Recover From Errors
* If the user clicks "Yes" in the modal window asking if they are requesting a COVID-19 vaccine, they are directed to another page that doesn't immediately explain why they weren't directed to the appointment-making process. Instead, the page they land on is essentially a general About page for COVID-19 vaccines. (2)

![After clicking Yes in the modal window box](../Images/clicked-yes.PNG)

> *Recommendation: Immediately explain why they can't make an appointment for COVID-19 vaccines at the time. Make sure the message is visible (e.g. in red and/or bold).*

#### 10. Help and Documentation
* If the user is on the help page, they want detailed information relevant to them. On Mayo Clinic's FAQ page on making appointments, there is simply a huge wall of text that the user must scroll through to find a question they *might* be looking for. (2)

<p align="center">
  <img src="../Images/appointment-faq.PNG" alt="Appointment FAQ page" width="500px"/>
</p>

> *Recommendation: Hide the text under each question to make it easy for users to scan through the possible questions and choose only content they are interested in. Organize the questions in a logical way. Include a downward arrow next to each question to show that information about that question can be found if they click each title. Use bullet points and numbered lists whenever appropriate.*

### Overall Assessment

The Mayo Clinic website is very large and contains a lot of information, so the main usability issues involve organizing the content and navigation in a way that is understandable for users. From an accessibility standpoint, they need to increase their font sizes and contrast between text and background, especially in the main navigation menu but also in other areas of their website. 



## Website 2: [Chinatown Service Center (CSC)](https://www.cscla.org/)

### About
[Chinatown Service Center (CSC)](https://www.cscla.org/) is a community-based Chinese-American health and human services organization that advocates for and provides services to immigrants and other communities. CSC's resources, including a Community Health Center that provides comprehensive healthcare, dental services, and behavioral services, are available in various Chinese dialects like Cantonese, Mandarin, Toishan, and Chiu Jou, as well as other languages like Vietnamese and Spanish.

My goal is to make their website much more usable, especially for primary users of CSC's services, including low-income, non-English speaking, and elderly users.

### Heuristic Evaluation

#### 1. Visibility of System Status
* When a user hovers over the top navigation menu, only the "Home" button changes color. The rest of the menu items do not provide color feedback, and simply displays the dropdown for each. Furthermore, it takes a while to load each dropdown at times. Users would have difficulty understanding whether the website is responding to their movement or clicks. There is, however, a color change to help the user recognize the page they are currently on. (3)

<p align="center">
  <img src="../Images/nav-services.PNG" alt="Navigation Menu, Services" width="350px"/>
</p>

> *Recommendation: Make sure that there is some kind of feedback (e.g. color change) when the cursor hovers over each menu item.*

#### 2. Match Between System and the Real World
* Some of the icons for the Community Health Center page do not entirely match our perception for each category. The happy face doesn't really reflect Behavioral Health and the Medical Clinic icon just looks like a house (the medical cross is very small). The tooth is also difficult to see when Dental Clinic is selected (and inconsistent with the other icons). (1)

<p align="center">
  <img src="../Images/community-health-center-icons.PNG" alt="Community Health Center icons"/>
</p>

*Recommendation: Use more literal and commonly accepted icons for the Behavioral Health and Medical Clinic icons (see examples [here](https://thenounproject.com/term/mental-health/3306335/) and [here](https://thenounproject.com/search/?q=medical&i=2468231)). Make sure icon styles are consistent as well.*

#### 3. User Control and Freedom
* The image carousel on the homepage moves very slowly and also responds to clicks very slowly, so users are surprised when they actually animate. It can be frustrating if users want to look through the gallery at their pace. (3)
* The image carousel on the Community Health Center page auto-forwards and moves much too quickly, to the point that clicking the small arrow controls doesn't allow the user to view the image they want to see (unless they realize they can click the image to see it in full screen), which is very frustrating. The carousel looks almost like an advertisement, which means it will likely be ignored. (3)

> *Recommendation: Test users to see what the right timing for carousels would be. There should be enough time for users to read the text and process the information on each image. Use bigger arrows so that users can easily click them, and make sure the carousel is responsive to clicks. Add a visual indicator to show where the user is in the image gallery.*

#### 4. Consistency and Standards
* The top navigation menu is not consistent with normal webpages, which makes it difficult to use and grow accustomed to. (3)

<p align="center">
  <img src="../Images/nav-bar.PNG" alt="Top Navigation Menu"/>
</p>

> *Recommendation: Reorganize the top navigation so that it complies with standards. For example, Hours & Locations can go under "About", Gala 2020 does not need to be displayed, and Vita 2021 should be kept under services (and should be renamed Free Tax Prep or something recognizable, since not everyone will know what VITA is).*

#### 5. Error Prevention
* Phone numbers change based on which tab of the Community Health Center page the user is on. However, it is difficult to recognize this because these phone numbers aren't displayed below the tabs. It is easy for users to call the wrong number or send an email to the wrong email address. (3)

<p align="center">
  <img src="../Images/behavioral-health-contact.PNG" alt="Contact information for Behavioral Health" width="550px"/>
  
  <img src="../Images/dental-clinic-contact.PNG" alt="Contact information for Dental Clinic" width="550px"/>
</p>

> *Recommendation: Put the tabs above the content so that users know what information is relevant to which department. Put the contact information in a consistent and easy-to-find location for each tap. Alternatively, direct users to a contact page where they can easily find where they should contact.*

#### 6. Recognition Rather Than Recall
* When you hover over the top navigation menu, there is no indication of which menu item's dropdown is being displayed, forcing users to recall which of the menu items they were looking at. This also makes it more difficult for users to remember how they got to a certain page in the future. (2)

<p align="center">
  <img src="../Images/nav-services.PNG" alt="Navigation Menu, Services" width="350px"/>
</p>

> *Recommendation: Connect the dropdown box with the menu item title to show that the dropdown is under that header.*

#### 7. Flexibility and Efficiency of Use
* There is no search bar on the website. Given the breadth of information and resources they provide, it would be very helpful to be able to search keywords that will lead users to the information they are looking for. (2)

> *Recommendation: Implement a search function to allow users another option to efficiently navigate through the website.*

* On the homepage, the first image is about free COVID-19 vaccines. The image, however, is not clickable and does not lead to another page with the details, as one would expect. Instead, the user must look through the website to find the full image/pdf. (3)

<p align="center">
  <img src="../Images/csc-homepage.PNG" alt="CSC homepage"/>
</p>

* I was able to find it under "Upcoming Events" at the bottom of the homepage, where users are unlikely to scroll to. Even then, the information was elusive - the carousel constantly autorotates through random images/pdfs of different events, and the only way to navigate through them is through the left and right arrow keys. Furthermore, although there is an Events category under "More" in the top navigation menu, it is not clickable. (3)

<p align="center">
  <img src="../Images/upcoming-events-2.PNG" alt="Upcoming Events carousel with free vaccine event information"/>
</p>

> *Recommendation: Because these free events are an integral part of CSC services, it makes sense to put a working Events link in the top navigation menu. On the Events page, separate upcoming events from past events. If possible, provide the information directly on the page rather than in image or pdf format so that users don't have to open another tab or window to view the information. Organize events by category, clearly provide dates and times, show relevant pictures.*

#### 8. Aesthetics and Minimalist Design
* Throughout the website, we see an unappealing interface due to incorrect placement of features, inconsistent fonts, colors, and other design aspects, low-quality images, cluttered and conflicting elements, and web developer mistakes. Altogether, the website is confusing for any user and lowers the credibility of the organization. The Community Health Center homepage, in particular, demonstrates this well. (3)

![CSC Community Health Center homepage](../Images/community-health-center-homepage.PNG)

> *Recommendation: Firstly, we need to fix the web developer mistakes so that the features are at least visible. For instance, the language switch needs to be fully visible so that users know they can switch the language of the website (important for the large, nonnative English-speaking user base). Next, de-clutter the website by reorganizing the information presented. For example, it is unnecessary to place the Community Health Center description at the beginning of every tab's page; use that real estate for the menu itself. Lastly, make sure that a design guideline is used so that font sizes, spacing, and colors are appropriate for seniors and consistent throughout.*

* The transparency of the tall fixed navigation menu dominates the layout of the page, and is very distracting. The menu is difficult to see and use, especially as users scroll down the page and there is text under the menu. (3)
* The social media icons don't need to be fixed because they can interrupt content. The user base likely doesn't use much social media anyways. (1)

> *Recommendation: Make the navigation menu opaque, and make it thinner by using the full width of the page and including only the necessary menu items so that more information can be displayed at a given time. Put social media icons in the footer, or at the top right if social media is actually used a lot by users (unlikely).*

#### 9. Help Users Recognize, Diagnose, and Recover From Errors
* When the wrong account information is entered on the patient portal, there is no indication of whether the username or password was incorrect (or both). (1)

> *Recommendation: Tell users which field is incorrect so that they can only fix what's needed.*

#### 10. Help and Documentation
* Virtually no help or documentation is provided on the website; the email and phone number are prominently displayed, so it is assumed that people would simply call or email to make an appointment. Important information (such as what insurance they accept, phone numbers for different departments) are randomly dispersed throughout the website. (3)

* A lot of information tends to be displayed via images and brochures, but it is difficult to find them. (3)

> *Recommendation: Consolidate important general information on one page so that users are not completely confused. Provide a link to the contact page instead of randomly displaying the phone number and email. Provide more guidance to users on each page; there are many different departments, phone numbers, and locations. For example, who, where, and when exactly should a person contact if they are a new patient?*

### Overall Assessment

A lot of work needs to be done in many areas, but the areas to focus on first are probably flexibility & efficiency of use and aesthetics & minimalist design. Their resources are invaluable to many low-income, immigrant families and their seniors, so being able to access that information easily should be prioritized. Also, an important feature to fix first is the visibility of the language switch, since many of their users may be Chinese monolinguals. The website is very harsh to look at in general, making it very difficult to use and makes CSC look unreliable. An update on aesthetics should therefore be one of their next steps.


