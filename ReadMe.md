# Flexbox Module Challenge

The module challenge is the afternoon project or assignment that students work through independently. This expands on the guided project completed earlier with the instructor.

## User Interface and Git

temp 2

## Objectives

- implement a CSS reset and understand why it’s important for cross-browser development
- identify and explain all properties in the box model
- describe and understand that flexbox is a module
- demonstrate understanding of flex container properties in flex box

## Introduction

In this challenge you will be building a simple portfolio website based on a wireframe of your choosing using the CSS principles covered today.

Portfolio websites are a great way to show off your work to friends, family, and future employers. As you progress through Lambda School you can update this site with projects you're proud of. Similarly, you can change the style, add a blog page, the possibilites are really endless.

## Instructions

### Task 1: Set Up The Project With Git

Follow these steps to set up and work on your project:

- [x] Create a forked copy of this project.
- [x] Add your Team Lead as collaborator on Github.
- [x] Clone your OWN version of the repository (Not Lambda's by mistake!).
- [x] Create a new branch: git checkout -b `<firstName-lastName>`.
- [x] Implement the project on your newly created `<firstName-lastName>` branch, committing changes regularly.
- [x] Push commits: git push origin `<firstName-lastName>`.

### Task 2: Minimum Viable Product

Once your repository is set up, practice what you learned today to create a portfolio site from the wireframe of your choosing. **You may choose any of the three wireframes in the "Wireframe Options" folder above.** Your complete project should look similar to the wireframe you chose, and include all of the following elements:

- [ ] A navigation bar with `About`, `Projects`, and `Contact` that link to the corresponding pages
- [ ] Gallery of projects created with flexbox - you may use random images in place of project screenshots for now with the random image link: https://picsum.photos/ or you may use images that mean something to you
- [ ] Information about you in place of the given placeholder
- [ ] A `My Projects` button that links to the projects page
- [ ] A `Contact Me` button that links to the contact page
- [ ] Links to any social media profiles (Instagram, linkedIn, Twitter) into the footer section of your home page

### Task 2b: Exit Ticket

Once you begin, you will have 15 minutes to answer the questions [here](https://app.codesignal.com/public-test/W7cjgvDN6BnmcCAJN/deNjYNsatrYjaN).

The completion of these questions is mandatory for MVP. However, passing the quiz doesn't affect your standing as a Lambda School student whatsoever. This is Lambda School testing itself! Please answer honestly and to the best of your ability _without_ using external references.

### Task 3: Stretch Goals

The following goals are designed to stretch your knowledge and may require additional research beyond what was learned in class today.

- [ ] Make your webpage work at different browser widths, including mobile
- [ ] Add CSS animations
- [ ] Design and execute your own wireframe for `About`, `Projects`, and `Contact` pages
- [ ] Host your website on Netlify.com

## FAQs

**What is a wireframe? How do I use one?**

_Wireframes are used to outline webpage styles, content, and functionality. UX designers will often use wireframes to explain their ideas to web developers. These wireframes, hand drawn or mocked up on software, are a cheap and easy way to iterate over designs. In this assignment you will chose a wireframe like the one below and create the elements with HTML and CSS._

![Screen Shot 2020-02-27 at 5.23.20 PM](https://i.imgur.com/b3riE65.png)

## Resources

👋 [Assignment help: A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

👀 [Explore a Curated Gallery of Professional Portfolios](https://wpamelia.com/portfolio-websites/#webdev)

🌼 [From Wireframes to Code](https://www.uxmatters.com/mt/archives/2010/12/from-wireframes-to-code-part-i.php)

## Submission format

Follow these steps for completing your project.

- [ ] Submit a pull request to merge <firstName-lastName> Branch into master (student's Repo). **Please don't merge your own pull request**
- [ ] Add your Team Lead as a reviewer on the pull request
- [ ] Your Team Lead will count the project as complete by merging the branch back into master

PART 2

# Responsive-Design

In this module challenge you will continue working on your portfolio website to make it compatible for different browser widths.

## User Interface and Git

## Responsive Design

## Objectives

- describe the differences in fixed, fluid, adaptive, and responsive layouts
- implement media queries in a project.
- describe how using scalable units for font sizes impacts accessibility and why designing accessible web pages is important

## Introduction

It goes without saying that this skill is essential for a professional Web Developer. Imagine trying to visit a store's webpage on your phone and not being able to even read the names of items? That would be totally unacceptable in this day and age! Same goes for a web developer's portfolio site.

In this challenge you will refactor your personal portfolio code to make it responsive. You have the ability to write HTML, CSS, and responsive media queries. You also know how to identify and write responsive units. It's time to put that knowledge into action!

## Instructions

### Task 1: Set up Project

New features of a project should occur in a new branch in the same repository. Follow these steps to set up and work on your project from yesterday:

- [ ] `cd` into your personal portfolio folder
- [ ] Create a new branch from `<firstName-lastName>`:

```bash
git checkout -b <firstName-lastName-day2> <firstName-lastName>.
```

- [ ] Implement the project on your newly created `<firstName-lastName-day2>` branch, committing changes regularly.
- [ ] Push commits: git push origin `<firstName-lastName-day2>`.

### Task 2: Minimum Viable Product

Use the checklist below to guide your work today. Your final product should be presentable at mobile, tablet and a desktop-width.

- [ ] Insert a viewport meta tag into the head of the project with these html attributes: content="width=device-width, initial-scale=1"
- [ ] Introduce max-width media queries into your project at 800px and 500px
- [ ] Add accessability features to your webpage
- [ ] Design should closely follow the [mobile wireframe](Wireframes/) given for your chosen layout

### Task 2b: Exit Ticket

Once you begin, you will have 15 minutes to answer the questions [here](https://app.codesignal.com/public-test/hALhPTQrbZCJtPYhn/F78eZwAGpSS3cR)

The completion of these questions is mandatory for MVP. However, passing the quiz doesn't affect your standing as a Lambda School student whatsoever. This is Lambda School testing itself! Please answer honestly and to the best of your ability without using external references.

### Task 3: Stretch Goals

Once you finish the minimum viable project, work on any of the following stretch goals:

- [ ] Test your website at several breakpoints and refactor code as needed. A few common breakpoints are below:
  - [ ] iPhone: 360×640
  - [ ] Laptop: 1366×768
  - [ ] Widescreen: 1920×1080
- [ ] Test your webpage's accessibility with a screen reader like [this](https://support.google.com/accessibility/answer/7031755?hl=en)
- [ ] Start over with min-width media queries to get a feel for how a mobile first approach would be like. I recommend making a branch of all your content in a new folder named "mobile-first" to keep it separate
- [ ] Test your webpage's accessibility with a screen reader like [this](https://support.google.com/accessibility/answer/7031755?hl=en)

## FAQs

**What if I'm not done with my site from last time?**

_If you're not totally happy with your site, that's fine. Try to work with what you have. If your challenge from yesterday is in a state that you **absolutely** cannot work on it, reach out to your TL for starter code and attend support hours for more HTML/CSS help._

**My site works on mobile - does that count as responsive?**

_A mobile website is **not** the same thing as a responsive website! A responsive webpage works at any browser width, not just mobile. Keep on coding!_

## Resources

📚[Best Practices for Responsive Design](https://www.browserstack.com/guide/responsive-design-breakpoints)

🤝[W3 Schools - Responsive Design](https://www.w3schools.com/html/html_responsive.asp)

👀 [Explore a Curated Gallery of Professional Portfolios](https://wpamelia.com/portfolio-websites/#webdev)

## Submission format

Follow these steps for completing your project.

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's Repo). **Please don't merge your own pull request**
- [ ] Add your team lead as a reviewer on the pull-request
- [ ] Your team lead will count the project as complete by merging the branch back into master.
