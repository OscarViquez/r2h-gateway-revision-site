# R2H-Gateway-City-Site-Revision
Link to live website
- https://puerto-vallarta-ohviquez.netlify.app/index.html

### Lighthouse Score: Home Page
![Image of my figma design file](/images/readme-audit-index.png)
### Lighthouse Score: Things To Do Page
![Image of my figma design file](/images/readme-audit-todo.png)
### Lighthouse Score: Contact Page
![Image of my figma design file](/images/readme-audit-contact.png)


### Accessibility Resources / Examples
- https://www.a11yproject.com/
- https://developer.mozilla.org/en-US/docs/Learn/Accessibility/HTML
- https://www.audioeye.com/
- https://npdigital.com/
- https://accessibe.com/product/examples
- https://www.accessibilitychecker.org/blog/examples-of-ada-compliant-websites/
- https://www.scope.org.uk/
- https://www.lonelyplanet.com/
- https://www.accessibilitychecker.org/

### Web Design Inpiration Resources / Examples
- https://dribbble.com/shots/15561002--Property-Buy-Sell-App
- https://www.airbnb.com/
- https://www.tripadvisor.com/
- https://www.airbnb.com/s/experiences?location_search=NEARBY
- https://www.airbnb.com/giftcards
- https://www.accessibilitychecker.org/

### Design System Examples
- https://www.designsystemsforfigma.com/


### The Process: Design
I decided to fully redesign my gateway project. I wanted to make my website look like a legitimate website.
 Something a person or business would pay if they asked me to build one.

I looked into websites like Airbnb and Trip Advisors to look how their information is laid out. As they are travel websites and are probably using best practices when it comes with design. I also looked for new pictures to add to the website to make it stand out a bit. Used Adobe Photoshop to crop or change the look of certain images.

I used Figma (https://www.figma.com/design/) to lay out the design before coding it out.
so I can just focus on accessibilty and semantic html structure when I start coding. 


### The Process: Coding
While I was coding the HTML Pages, the website I constently used as reference was the (https://www.a11yproject.com/). Main reason being that the whole website was created with Accessibility as their priority. Another reason being how well they scored on lighthouse (All 100% Score). I would specifically observe how they have layed out the semantic elements on the footer. Since the design I chose for my footer was a bit complicated, I had to becareful on how I had it structured for accessibilty and best practice.

I had problems with Flexbox in my article sections of the To-Do Page. Containers would overlap when screen size is shrinking and I didnt know why. So I decided to only apply one conatiner a 50% width, and that fixed the issue. 

I added aria-labels to sections that needed them, based off the Lighthouse audit. Changed Image format on larger pictures from png to webp to improve performance. Added a black baground behind images. The black background will be a backup, just in case if image doesnt load and the text needs to be visible.

![Image of my figma design file](/images/readme-design-figma-intro.png)




