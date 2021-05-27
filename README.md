# Mayo Clinic Redesign - Delivering Health & Healthcare Information to Seniors
By Emily Dong
---

### Introduction
According to the United Nations, the number of seniors (65+) is expected to double to 1.5 billion by 2050 globally. Despite seniors being one of the fastest-growing and wealthiest demographics in wealthy countries, many digital products fail to meet senior accessibility needs and have made them feel excluded from an online world that is unfriendly to those with bad eyesight, declined dexterity, and unfamiliarity with the web. In particular, health is a major concern among seniors, and we should ensure that information is accessible to them. 

For this project, I hope to demonstrate how we can improve user (patient) experiences on websites with health, healthcare, and patient information so that seniors can maintain their well-being. Additionally, by designing for their accessibility, we are designing for everyone's accessibility.

### Design Statement
[Mayo Clinic](https://www.mayoclinic.org/) is a non-profit American medical organization dedicated to clinical practice, education, and research, and whose location in Minnesota has been recognized as the best hospital of 2020-2021 by U.S. News & World Report. Mayo Clinic is a trusted source of medical information about diseases and conditions, possible causes for symptoms, drugs and supplements, tests and procedures, and healthy living. The website is also used by patients to make appointments, access their patient account, and find information about receiving care. The richness of health information and breadth of features on the Mayo Clinic website can be both valuable and overwhelming. My goal is to preserve the value while streamlining the user's ability to navigate throughout the website. 

### Competitor Analysis: Heuristic Evaluation

Jakob Nielson's [10 Usability Heuristics](https://www.nngroup.com/articles/ten-usability-heuristics/) Explained

[Severity Ratings](https://www.nngroup.com/articles/how-to-rate-the-severity-of-usability-problems/) for Usability Problems by Nielsen Norman Group

### Usability Testing

**Usability testing (UT)** is needed in order to confirm these concerns and perhaps identify other usability issues that may diminish the user experience. By observing where users encounter problems or points of confusion while performing a set of tasks, we can obtain empirical data and identify opportunities to improve elements of the website, app, or other product. Furthermore, UT allows us to gain an in-depth understanding of the user's perspective, and with these insights, we can create products that will not only meet users' needs, but will also lead to customer satisfaction and be competitive in the market. If usability testing is done early and often throughout product development, we minimize the need to correct mistakes down the road, saving stakeholders a lot of time, money, and effort.

A pilot usability test (UT) was conducted in order to assess the materials, setting, and software used for usability testing. Due to limited formal testing space, the pilot UT was conducted in a minimalist portable test lab set up in a home setting. A laptop was used to run Zoom to record the user's facial expressions along with interactions with the website, and another laptop was used for the participant to fill out the [survey](https://docs.google.com/forms/d/e/1FAIpQLScKkK4JFiPDIyvAw645oKG36WBJO_igeXGJS6PRohB4tHtyTA/viewform?usp=sf_link). The moderator sat next to the participant.

The usability test and website of interest was first introduced to the participant, and the participant was given an informed consent form to sign. They were given pre-test questions regarding either their previous experience with the website, which might influence test performance, or their first impressions of the website. Keeping in mind the usability concerns mentioned before, the participant was then asked to perform 3 tasks:

<iframe src="https://drive.google.com/file/d/1NBCB_01-NReN6Kc6yMDuIweXLQnG1v2W/preview" width="640" height="480"></iframe>


### User Research [Contextual Inquirty]

I visited a senior, minority-group user and independently conducted contextual inquiry in order to gain a better sense of the environment in which seniors would normally access health information and to use those insights in redesigning the Mayo Clinic website to be more accessible for them. The session was therefore held at the user's home, and audio of the session was recorded and transcribed using Otter.ai on my phone with permission from the user. Field notes and observations of user behavior were taken on a laptop.

#### Materials
* [Contextual Inquiry Guide/Script](https://docs.google.com/document/d/1zNHiBzdG5Y8lv5J38GJoqpJONRAYYMMKfFZCLkaLXdY/edit?usp=sharing)

#### Data
* [Audio + Live Transcript of Interview](https://otter.ai/u/143CuTXnuweLRTeHz_ZRM0jk-Os)
* [Transcript of Interview Only](https://docs.google.com/document/d/1wEfhU8yfb0pqXnI6XKYqwaGexaXYt36zgwX7lbkksfI/edit?usp=sharing)
* [Field Notes](https://docs.google.com/document/d/1oOFrh0s3qjZ9RsDALjlodB7VDqvL728tthr8Z_610KA/edit?usp=sharing)


### UX Storytelling

Storytelling is needed for building empathy. It gives us the ability to create a shared understanding of why we are building a feature, and it serves as an important medium for communicating difficult concepts in a logical way. It also focuses us on the perspective of the user, allowing us to understand the reasons behind a user’s actions and reminding us that *we are not the user*. Storytelling can also facilitate generation of new ideas and can be used to convince key stakeholders to make decisions that will benefit the user in addition to the business.  

<table>
  <tr>
  <td><p align="center">
      <img src="https://raw.githubusercontent.com/emilydong001/DH110/main/Images/persona-vincent.png" alt="Vincent's Empathy Map" height="300px"/> 
      </p></td>
  <td><p align="center">
      <img src="https://raw.githubusercontent.com/emilydong001/DH110/main/Images/persona-taylor.png" alt="Taylor's Empathy Map" height="300px"/>
      </p></td>
  </tr>
</table>


<table>
  <tr>
  <td><p align="center">
      <img src="../Images/empathy-map-vincent.png" alt="Vincent's Empathy Map" height="500px"/> 
      </p></td>
  <td><p align="center">
      <img src="../Images/empathy-map-taylor.png" alt="Taylor's Empathy Map" height="500px"/>
      </p></td>
  </tr>
</table>

<p align="center">
  <img src="../Images/user_journey_vincent.png" alt="Vincent's Scenario and User Journey"/>
  <img src="../Images/user_journey_taylor.png" alt="Taylor's Scenario and User Journey"/>
</p>

### Wireframe and Graphic Design Element Variation

#### Design System

##### Typeface
Unfortunately, I could not access the exact typeface from the Mayo Clinic branding guidelines (only the homepage could be viewed). I chose two fonts that were the most similar based on an online [font identification tool](https://www.myfonts.com/WhatTheFont/), the Ariata font family and the Bw Nista font family.
* **Ariata:** Use for larger headlines or visual contrast, 48 pt for titles, 36 pt for subtitles
* **Bw Nista:** Use for smaller copy, 16 pt for small copy (e.g. breadcrumbs), 18 pt for body copy, 24 pt + bold for headings and 20 pt + bold for subheadings

##### Color Scheme

**Light-mode:** 
* Background: #FEFEFE
* Primary (default text): #263238
* Focus: #0057B8
* Secondary Focus: #E1EFFF

**Dark-mode:** 
* Background: #263238
* Primary (default text): #FEFEFE
* Focus: #E1EFFF
* Secondary Focus: #505963

##### Layout Grid and Spacing
* **Layout grid**: I didn't use a specific grid for every page, but I kept the margins at 72px to allow for "breathing room" on each side. I had one column for text in the middle, which helps guide the reader down the page. I also two columns on the left and right - the left is thinner and would be reserved for the clickable outline for the majority of the page, and the right is wider for advertisements, related information, etc.
* **Line-spacing between body text**: 150% for readibility and legibility


### Low-fidelity Prototype

My project is to redesign the Mayo Clinic website to make it more consistent and intuitive to use. Currently, the website has too many duplicate links, competing features, and irregular hierarchies, which can lead to confusion and choice paralysis in users. In an attempt to satisfy the requirements of two [personas](https://github.com/emilydong001/DH110/blob/main/Assignments/Assignment04.md), I wanted to incorporate a few new features:

1. **Clickable outline/overview:** Allows the user to quickly navigate to different parts of the article
2. **Breadcrumbs:** Displayed consistently at the top of each article; can be used as alternative navigation and gives the user a sense of where they are on the site
3. **Search feature on each health information subcategory (e.g. Diseases & Conditions, Symptoms, Tests & Procedures, Drugs & Supplements):** Allows the user to search by typing rather than only search by first letter
4. **Section that leads to Mayo Clinic Connect:** Briefly introduces the user to Mayo Clinic Connect and allows them to directly go on that site to discuss personal health-related stories with other patients and/or caregivers (as I understand, the main Mayo Clinic site currently does not have a link to Mayo Clinic Connect).

I also wanted to simplify the website to only the necessary componenets and reorganize the website so that the abundance of health information is clearer and easier to access, especially for older, less tech-savvy users.


### High-fidelity Prototype

Link to interactive prototype [here](https://www.figma.com/proto/UIjfi4ADU1IkrE7mkrhKkn/DH110-Assignment06?node-id=131%3A569&scaling=scale-down-width&page-id=0%3A1).

<iframe style="border: 1px solid rgba(0, 0, 0, 0.1);" width="800" height="450" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2FUIjfi4ADU1IkrE7mkrhKkn%2FDH110-High-Fidelity-Prototype%3Fnode-id%3D131%253A569%26scaling%3Dmin-zoom" allowfullscreen></iframe>

### Evaluation and Revision History

One user commented that the original placement of the clickable outline was difficult to see, though this may be due to the limited interactions that could be prototyped (e.g. the outline is not sticky). Still, in response to this, I removed the overview box and moved the outline up so that it is visible right under the secondary navigation bar. I also removed the box around the outline to make the interface less cluttered.

<p align="center">
  <img src="../Images/diabetes-page-before.PNG" alt="Diabetes page before changing position of clickable outline" width="450px"/>
  <img src="../Images/diabetes-page-after.PNG" alt="Diabetes page after changing position of clickable outline" width="450px"/>
</p>

One user commented that they thought it felt like a business website - serious and professional. I did want the website to have that impression, but I also wanted the site to look more welcoming. Ideally, I would switch the landing page photo to one that captures a happier experience for the patient, but free stock photos on Unsplashs, Pexel, and other similar websites are limited in their selection of choices. I also made sure to round off the corners of all the buttons to emphasize the more friendly atmosphere. They also commented that it was difficult to see the language toggle at first, which is especially important for accessibility. In response to this, I moved the language option more towards the left so that the user can see it more readily in the top navigation:

<p align="center">
  <img src="../Images/top-navigation-before.PNG" alt="top navigation before changing position of language toggle"/>
  <img src="../Images/top-navigation-after.PNG" alt="top navigation after changing position of language toggle"/>
</p>

### Pitch Video

### Conclusion
