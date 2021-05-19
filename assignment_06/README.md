# Assignment 6: User Interface Design: High Fidelity Prototype (Part 1)
### Aditi Melkote, DH110

## Overview

**Project description:** The aim of this project is to create a platform that will provide guidance to individuals interested in starting gardening. It aims to do so by providing beginners personalised recommnedations for plant growth and care, as well as access to clear, understandable instructions and advice. Through this app, I hope to help beginners not only cultivate their plants, but cultivate their interest in gardening and plant care as well.

**Purpose of high-fidelity prototype:** The purpose of this high-fidelity prototype is to visualise the various interfaces and functionalities within this app. By visualising the interfaces in a format users are familiar with, I hope to gain an understanding of how they will interact with the app, what features and functionalities they find useful or not, and make any improvements accordingly to enhance the overall user experience of the app.

**Process:** This high-fidelity prototype has been the culmination of research and information gained from previous steps including usabability testing, contextual inquiry and interview, persona creation, as well as low-fidelity prototyping. These previous steps have allowed me to gather valuable data regarding target users' thoughts, needs, and concerns about starting gardening, features they liked/disliked in other gardening apps and websites, features they would like to see in an app such as the one being prototyped here, as well as their natural interactions with the flow of interfaces in the low-fidelity protoype. Based on observations and feedback from the previous steps, I have made some improvements to my interfaces and features from the low-fidelity prototype to create the following high-fidelity prototype using Figma, incorporating necessary features of user interafce design. The high-fiedlity prototyping will also involve conducting an accessibility check to ensure it is WCAG2.0 AA compliant, as well as an impression test to understand users' initial impressions and perceptions of the prototype interfaces.

**Tasks:** (a) Receive personalised recommendations on which plants to grow; (b) Access plant care information (how many times to water plants, what fertiliser to add, how much sunlight they need, troubleshooting and faqs) for chosen plants; and (c) Set up plant care tasks for chosen plants

## Wireframes and Wireflows
### Task 1 wireframes and wireflow:
<img src="/images/t1frames.png">
<img src="/images/t1flow.png">

### Task 2 wireframes and wireflow:
<img src="/images/t2frames.png">
<img src="/images/t2flow.png">

### Task 3 wireframes and wireflow:
<img src="/images/t3frames.png">
<img src="/images/t3flow.png">

## Interactive Prototypes
Interactive prototype for **first task** can be accessed using this [link](https://www.figma.com/proto/f7e0D0pwHLVgErHCEI2HDe/Interactive-prototype-Task-1?node-id=1%3A2&scaling=scale-down&page-id=0%3A1)

Interactive prototype for **second task** can be accessed using this [link](https://www.figma.com/proto/zuq9lg47KWCb4FZGsvBcqn/Interactive-prototype-Task-2?node-id=1%3A3&scaling=scale-down&page-id=0%3A1)

Interactive prototype for **third task** can be accessed using this [link](https://www.figma.com/proto/CEdb73Qh7WX6AtRZPXPB3q/Untitled?node-id=1%3A6&scaling=scale-down&page-id=0%3A1)

## Three design variations
The following are three design variations of the "add-task-1" screen (see (c) above). The three variations are yellow-tinted, which is the main theme, a darkmode variation, and a lightmode variation.

<img src="/images/three-var.png">

## Design System
- **Typeface family + size**
> The type face used for the representative screens/wireframes for each feature is Helvetica Nueue. This font was chosen as it is a default font in iOS devices, in addition to being a sans serif font which makes it easy to read and comprehend, and thus more accessible to a greater number of users. This font is simple and elegant, and for users familiar with the font through their devices, it helps give a friendly, sympathetic, and kind feeling. These are the feelings I want to evoke in my target users, who will be beginners to gardening and thus in unfamiliar territory - through the use of a familar font, I hope that it will contribute to help them feel more at ease as they begin their gardening journey with the app. 
> It was used primarily in **Bold** for titles and subtitles, and in bold italics when giving explanatory information for certain buttons (see the maintenance question in the first task wireframes, and the plus button in the third task wireframes). The font was bolded to comply with and enhance accessibility. For the darkmode variation, I used the font Open sans, again in Bold and for the lightmode variation I used the font Asap in Bold. I chose these fonts again because they were sans serif and hence more accessible. Asap in particular is quite rounded which makes it look closer to handwriting, and thus more friendly and welcoming to the user. As for size, I used a variety of sizes - for most of the titles, such as "Hi Adi!" in task (a), "Pink Rose" in task (b), and "My Plants" in task (c), I used font size 50, as I found this was a nice size to empahsise the titles without making them seem too large or overbearing to the user. For the content text, I used sizes ranging between 22-25px, in Bold. I used 22px in the text for the first task wireframes; and 25px in the text for second and third task wireframes. Once exception is that in the drop down box in task 2 wireframes, I used 15px font. roughly half of the title size, to clearly demarcate between the title and content text.
- **Color scheme:**
 >  Overall the colour scheme of consists of variations of dark greens, red-pinks, and whites. For all colours used, opacity is 100% unless otherwise specified. 
 >    - Background - I used a light tinted yellow-green colour (#F8FFF0) for the background, instead of a bright white, to make the interface more accessible. The light yellow-green was also used to evoke a sense of being in nature, in a garden, to keep with the theme and purpose of the app. In the darkmode variation, I used a dark grey (#000000, opacity 63%) for the background, keeping with the darkmode theme, and for the lightmode variation I used a white background (#FFFFFF) to emphasise this basic, lightmode theme. 
 >   - Text - For text, I used either a dark green (#025918), or white (#FFFFFF, against a darker background). The dark green was chosen again in accordance with the nature/garden aesthetic I want to create, and the dark green can be observed in the title text and some body text in the first feature (personalised recommendations). I used white for the title text in the second and third features, against a darker background, just for some visual contrast and to create visual interest. 
 >  - I also used a red-pink colour (#F27B50) for buttons in task 1, and for the names of plants in Task 3; a lighter red-pink colour (#FFD3C2) was used as the background for that tabs for each plant in task 3. as well as text, to evoke a floral aesthetic in line with the garden theme. Overall in terms of the hue and saturation, I tried kept all the colours I used warm in order to help the user feel comfortable, as though they are in a kind and friendly environment.

- **Layout grid and spacing**
> For the first feature, the layout primarly consisted of nine rows and two columns (for the back < and next > buttons); the second feature involved nine rows again but no columns since there are no buttons at the bottom for this feature, and for the third feature, again I implemented nine rows but no columns. For text spacing, whenever there was a block of text I ensured that the spacing between lines is equal to 1.5x the font size - this was again implemented to ensure greater accessibility. All the content text in Task 1, 2 and 3 is left-aligned. The buttons in Task 1 are left-aligned only in the first wireframe, and then they are center-aligned in the question wireframes. In general, all components for all wireframes in all tasks have a 16px margin from the edge of screen frame on all sides. 
> 
> I also made the buttons, icons and tabs have rounded edges, again to create a sense of friendliness and comfort in the interface for beginner gardeners. 


## Accessibility test
These are screenshots from the colour contrast check test using the Spark plugin in Figma. 

<p float="left">
  <img src="/images/contrast-1.png" height="300px" /> |  
  <img src="/images/contrast-2.1.png" height="300px" />
</p>

From the above screenshots we can see that the dark green colour used for the titles and other body text is accessible according to the WCAG2.0 AA level criteria. The pink-red coloured text used in some titles is also when the font at least in Bold weight or 24 px, which, from the second screenshot, we can see that the text is 30px and Bold, thus making it compliant and accessible according to the WCAG2.0 AA level criteria.

## Impression test
### Quotations from user:
- "Overall seems quite easy to use - it looks very natural and garden-y"
- "Love the colours. The orange-pink and green colour against the light, pastel yellow background is very pleasant and soothing to see"
- "There seems to be a mismatch between the text size and button size here - the third button has smaller text "(this was specifically in reference to buttons on the indoor-outdoor question screen in feature (a))
- "The text seems a bit congested along with the image, too compact" (in reference to the drop-down box in the second screen for feature (b))
- "The add task icon is very clear and intuitive, I like that" (referring to feature (c))
- "I think the three icons should be smaller and along the top instead of the side" (in reference to the three icons for each plant in feature (c))
- "The 'My Plants' title seems a bit too big"
- "Oh I really like the dark mode version!"

## Cognitive Walkthrough
Screen recording for **Task 1** can be accessed through this [link](https://drive.google.com/file/d/1AFa_3JbC-qA5BcNWuys2sThaFwMgr9xl/view?usp=sharing)
Screen recording for **Task 2** can be accessed through this [link](https://drive.google.com/file/d/1GcRI91Na6sCkbtCULvL49Yjc8p3lKZbn/view?usp=sharing)
Screen recording for **Task 3** can be accessed through this [link](https://drive.google.com/file/d/1Ken-WjBbFLTY88goo7gm-JtzdhnXUKOz/view?usp=sharing)

**Summary of cognitive walkthrough:**
In general, the user was able to understand the purpose of each task, and how to proceed with it. I received feedback that for the first task, I should improve the horizontal scrolling feature in the last wireframe, as it wasn't very obvious to them that they should scroll. They suggested that I go for a grid like structure with different tiles for each plant, such that all recommended plants can be seen on the screen instead of scrolling plant by plant with the horizontal scroll. For the second task, the user was able to get through the task well, but I realised it would have been more logical to have the representative drop down on the first "About this plant" tab, instead of the "Soil Type" tab. I saw this when the user tapped on the first tab titled "About this plant", but the interactive prototype was configured such that the user had to tap on the "Soil Type" tab. The user, who is a beginner gardener and thus part of my target audience, also suggested that I add a video of the plants in addition to the image in the second task/feature, as a feature they would find useful. In case of the third task, the user said that the icons were clear in terms of their purpose and function, and were able to go through the add task feature and return to the My Plants screen with relative ease. 


## Reflection
Summary of the process, what went smoothly or differently from your expectation
Overall, I found this process of designing the high-fidelity wireframes and wireflows, and then the interactive prototype quite challenging but interesting at the same time! It helped me learn how to use Figma, which I had not used before. I also understood the value of trial-and-error when creating the interactive prototype, as it forced me to think of how a user who was not familiar with the app would go about navigating through it. In terms of the process, the high-fidelity prototyping began with creating the wireframes based on my low-fidelity prototype - this involved making a lot of decisions regarding the layout, colour scheme, and ensuring that the interface was accessible. As described in the design system section, I chose colours and fonts that evoke a sense of being in nature, as well as convey feelings of friendliness, comfort and kindness, so that my target audience of beginner gardeners would be put at ease when encountering and navigating the app. Colour-contrast testing was conducted to ensure that the interfaces were WGA2.0 AA level accessible. Following this, I added interactions to the wireframes to create the wireflow for each of the tasks, and then proceeded to create the interactive prototypes for each task. I also conducted an impresssion test and cognitive walkthrough to understand the user's thought process and expreience of using the app and perfoming the tasks on the interactive prototypes, and was able to receive some good feedback on what I can improve. 


