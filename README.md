# <img src="https://cloud.githubusercontent.com/assets/7833470/10423298/ea833a68-7079-11e5-84f8-0a925ab96893.png" width="60"> Project One

It's time to put everything that you've learned in the past month together! For your first project, you will build a full stack web application using jQuery and AJAX, Express, Node.js, Mongoose, and MongoDB.

Apply the skills you've learned by building a full-stack web application from the ground up, and build a polished, published website you can share in your portfolio.

You will be working in pairs for this project.  Show us what you've got!


## COMPLETED PROJECT DELIVERABLES

* Completion of the **technical requirements**
* On your personal site:
   - A link to your **website hosted on Heroku**
   - A link to your **source code on GitHub**
* A **brief presentation**, in the company of friends, highlighting triumphs, challenges, words of wisdom, and 3-5 lines of code you want to share with your classmates, copied into a separate document (probably your readme).  Each developer MUST present half of your presentation.

## TECHNICAL REQUIREMENTS

For this project, there are core technical requirements and flex technical requirements. You must complete all of the core technical requirements and 2 of the 5 flex technical requirements.

### Core Technical Requirements

**Your app should have all of the following:**
* **Express API** - Build an Express server that has both HTML and JSON endpoints.
* **RESTful Routes** - Design your CRUD routes using the [RESTful routing](https://github.com/sf-wdi-34/mongoose-associations#restful-routing) convention.
* **AJAX** - Leverage AJAX to make requests asynchronously.
* **jQuery** - Use jQuery to add interactivity and display data on the client side.  
* **MongoDB** - Persist at least two resources to a MongoDB database. One resource must have full CRUD.  
* **Visual Design** - Make your front-end snazzy by adding custom styling. First impressions matter!
* **Code Style** - Write professional-looking code. Use a consistent style. Consider following the [Airbnb Javascript ES5 Styleguide](https://github.com/airbnb/javascript/tree/es5-deprecated/es5).
* **Git** - 40+ commits, with a significant number from each teammate. Commit early, and commit often. Each commit message should give a clear idea what you changed. (And don't expose any secret keys/tokens on GitHub!) You can reference our [GitHub collaboration workshop](https://github.com/sf-wdi-34/github-collaboration) and the [in-depth GitHub collaboration writeup](https://github.com/SF-WDI-LABS/shared_modules/blob/master/how-to/github-collaboration-workflow.md).
* **Heroku** - Deploy your app with Heroku.
* **Documentation** - Write a README that would make an employer excited to hire you. See this [example readme](https://github.com/SF-WDI-LABS/readme-example/blob/master/README.md) for a suggested structure.

### Flex Technical Requirements

**Your app should have 2 of the 5 following features:**
* **External API** - Use an external API to integrate rich data into your app.  If you need to make API requests from your Node.js server, we recommend using a package like [request](https://github.com/request/request) to make request syntax simpler.
* **Data Validation** - On the client side, give users a visible error message if they try to submit blank forms (or other validation failures), explaining why they weren't allowed to submit.  Also, in your database, use mongoose's validations for at least one attribute for each of your schemas (see <a href="http://mongoosejs.com/docs/validation.html">mongoose validation docs</a>). You can meet this requirement with just mongoose's built-in validations, but you could also take it further with custom validations.
* **CSS Grid Library** - Use Materialize, Twitter Bootstrap, Foundation, Skeleton, or another CSS framework throughout your site to create a unified baseline style.
* **Model Relationship** - Create a one-to-many or many-to-many relationship between two models using either embedded or referenced data.
* **Sessions** - Research sessions and use them to track a visitor.  As a much larger challenge, you can use sessions to enable authentication (user sign up, log in, and log out).  Note: This option requires significant independent research, and doing authentication  is especially difficult.  There are some resources from past WDI cohorts: [33](https://github.com/sf-wdi-33/express-simple-auth), [24](https://github.com/sf-wdi-24/express-microblog/tree/solution-auth), but do not underestimate this challenge.


## BONUS IDEAS  
If you want to push yourself and learn something new, optionally consider doing some of the following with your app, but *please talk to an instructor* beforehand:

* **More Models or Relationships** - Add another model to your project or create a new relationship.
* **Model Methods** - Level up your models by adding a method to one of your schemas.  For example, a person schema with `firstName` and `lastName` can have a `fullName` method (see mongoose docs on [instance methods](http://mongoosejs.com/docs/guide.html#methods) and [static methods](http://mongoosejs.com/docs/guide.html#statics)).
* **Sass** - Use a CSS pre-compiler to write more imperative CSS.
<!-- * **WebSockets** - Break out of the request/response cycle and use websockets to send realtime updates to the client(s) when the server changes. -->

## PLANNING DELIVERABLES

Now that you know the full requirements for your app, carry out more detailed planning.

**Prepare the following planning deliverables, and meet with an instructor to have your plan approved.** (Feel free to read over notes on [Software Development Best Practices](https://github.com/SF-WDI-LABS/software-development-best-practices).)
*  **Minimal Scope** - Manage complexity. You probably won't have time to build a "spaceship" version of your project idea. Figure out the simplest thing you can build that meets the project requirements, and start with *that* version of your app.  
  ![iterative-design](https://cloud.githubusercontent.com/assets/7833470/11330092/f76e7c50-9159-11e5-875f-748817e41afc.png)
* **User Stories** - Outline your core user stories. Once you start to build, you'll divide these into clear, smaller steps (sometimes called "development stories").  Make sure you track development stories once you start implementing, not just the broader user stories.
* **Wireframes and Site Flow** - Sketch out what UI elements the main pages will include and how the user will navigate from page to page.
* **Database** -  List the schemas you'll need, and list the attributes for each.  Indicate any associations (relationships) you plan to have in your data.
*  **Feasibility Check** - Research any new tools or APIs. For example, if you're using an external JSON API, is all the information you want included in the response? Do you need to sign up and wait for approval to use the API?  Are there API keys you should keep hidden?

Once your project has been approved, one member of your group should create a **GitHub Repo** for your project and [add your partner as a  collaborator](https://help.github.com/articles/adding-collaborators-to-a-personal-repository/).

We recommend also setting up a [Trello](https://trello.com/) board to track your progress, communicate with each other, and keep focused on the most important goals.  Here's a [sample trello board](https://trello.com/b/k42peuus/tunely-sample-project-trello).


## TEAMWORK EXPECTATIONS

Every team member shares the responsibility of creating a product that reflects the viewpoints and contributions of each team member. If you're already more outgoing or vocal about your ideas, this will probably mean taking a back seat sometimes or asking for input from quieter teammates. If you're one of those quiet people, make a dedicated effort to speak out more! This will help you create a project that's better than what you would have come up with individually.

Communicate,communicate, communicate! Discuss roles, expectations, and timetables before you start coding. Figure out how you want to communicate about the project when you aren't physically with your team.

## TIMELINE

> DO NOT START CODING UNTIL YOU HAVE GONE OVER YOUR PROJECT PLAN WITH AN INSTRUCTOR.


* **Monday, April 17th @ 3:00pm** - Groups assigned and initial planning.

* **EVERY DAY during project week @ 9:15am** - Technical interview preparation.

* **BEFORE Tuesday, April 18th @ 12:30pm** - Present your app plan to an instructor to go over your [planning deliverables](#planning-deliverables).

* **Friday, April 21st @ 3:00pm** - Project due and presentations!



In addition, we suggest you have a feature freeze by 9:00am on Friday, April 21st - meaning no new features! After a feature freeze, you can focus on re-deploying your code to Heroku, polishing existing features, finalizing your README.md, and planning your presentation.

## FEEDBACK

**Your project will be evaluated based on the following criteria:**

* **Project Workflow**: Did you complete the user stories, wireframes, and task tracking as specified above? Did you use source control as expected for the phase of the program you’re in (detailed above)?
* **Technical Requirements**: Did you deliver a project that met all the technical requirements?
* **Creativity**: Did you add a personal spin or creative element to your project? Did you deliver something of value to the end user?
* **Code Quality**: Did you follow code style guidance and best practices covered in class, such as spacing, modularity, and semantic naming? Did you comment your code?
* **Problem Solving**: Are you able to defend why you implemented your solution in a certain way? Can you demonstrate that you thought through alternative implementations?

Each of the criteria above will be evaluated as one of **incomplete**, **does not meet expectations**, **meets expectations**, or **exceeds expectations**. You'll be receiving written feedback from your instructors.


### HAPPY CODING :)
