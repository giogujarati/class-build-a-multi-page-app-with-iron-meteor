
## <a href="https://www.eventedmind.com/classes/build-a-multi-page-app-with-iron-meteor-6737880d" target="_blank">Class: Build a Multi Page App with Iron Meteor</a>

**Meteor**<br>
****

In this class we'll build a more sophisticated, multi-page application in Meteor. We'll use the iron scaffolding tool to create project structure and boilerplate code. In addition to understanding the concepts of a multi-page app, we'll build several features including multiple users, a comment system, and a customized Meteor Developer Accounts OAuth login.

**What's in this class?**


* <a href="https://www.eventedmind.com/classes/build-a-multi-page-app-with-iron-meteor-6737880d/introduction-bba87c88" target="_blank">Introduction: Build a Multi Page App with Iron Meteor</a> - Introducing the Build a Multi Page App with Iron Meteor class.

* <a href="https://www.eventedmind.com/classes/build-a-multi-page-app-with-iron-meteor-6737880d/creating-the-project-with-iron-scaffolding-5e82f45b" target="_blank">Creating the Project with Iron Scaffolding</a> - The iron command line tool let's us quickly create a project structure and scaffolding. It can automatically create the files and code for collections, routes, controllers, templates and other project resources. It also lets us run Meteor projects with settings for different environments like development, staging and production. We'll be using the iron command line tool in the rest of the class to save time building the application.

* <a href="https://www.eventedmind.com/classes/build-a-multi-page-app-with-iron-meteor-6737880d/the-master-layout-7e5ed192" target="_blank">The Master Layout</a> - A layout will allow us to reuse a look and feel across multiple pages in our app. It's where we'll put things like the login buttons, navigation breadcrumbs, and general container divs. You'll also see how the iron:layout package used by iron:router allows to create multiple yield regions which we can render content into from child templates.

* <a href="https://www.eventedmind.com/classes/build-a-multi-page-app-with-iron-meteor-6737880d/routes-and-controllers-42debfff" target="_blank">Routes and Controllers</a> - In this introduction we'll tour the route and controller for the home page of the app. Routes allow us to map a url to a controller. Controllers are a way of organizing our application logic into classes.

* <a href="https://www.eventedmind.com/classes/build-a-multi-page-app-with-iron-meteor-6737880d/customizing-login-with-meteor-oauth-c0ef2966" target="_blank">Customizing Login with Meteor OAuth</a> - Meteor has packages for multiple OAuth providers including Facebook, Github and several others. Meteor also provides their own OAuth service called Meteor Developer Accounts. In this video you'll integrate with Meteor Developer Accounts and customize the UI. You'll also see how to store API configuration settings for development and production environments as environment variables.

* <a href="https://www.eventedmind.com/classes/build-a-multi-page-app-with-iron-meteor-6737880d/collections-and-subscriptions-c0d941be" target="_blank">Collections and Subscriptions</a> - The iron tool will generate a secure collection for us using Meteor's allow/deny functions. You'll see how to customize the security rules. Then you'll write the publish and subscribe functions and use the WebSockets console to confirm the correct messages are being sent over the wire.

* <a href="https://www.eventedmind.com/classes/build-a-multi-page-app-with-iron-meteor-6737880d/generating-templates-5fda3572" target="_blank">Generating Templates</a> - Use the iron tool to generate scaffolding for the main templates. You'll see a workflow for creating several templates quickly, and wiring them up to work together. By the end of this video the home page will be complete.

* <a href="https://www.eventedmind.com/classes/build-a-multi-page-app-with-iron-meteor-6737880d/routing-with-parameters-e83c5f73" target="_blank">Routing with Parameters</a> - In this lesson you'll create a route for looking at specific todos. The route will have a dynamic parameter for the todo id. Then you'll subscribe to data using the id parameter and set a global data context for the page's template. You'll also see a technique for debugging problems.

* <a href="https://www.eventedmind.com/classes/build-a-multi-page-app-with-iron-meteor-6737880d/using-reactive-state-928d23fb" target="_blank">Using Reactive State</a> - Sometimes you want to reuse the same template in different routes. For example, you might have a route for showing a template and another route for editing the todo. You can use reactive state to decide whether to render the show view or edit view.

* <a href="https://www.eventedmind.com/classes/build-a-multi-page-app-with-iron-meteor-6737880d/adding-multiple-users-7d03e6c5" target="_blank">Adding Multiple Users</a> - In this lesson you'll add a feature to see other users' todos. Now that you're familiar with the scaffolding concepts, we'll rapidly move through the workflow of building this feature, including the route, templates, breadcrumb content, and publish functions.

* <a href="https://www.eventedmind.com/classes/build-a-multi-page-app-with-iron-meteor-6737880d/adding-comments-2c04a389" target="_blank">Adding Comments</a> - Now that we can see other users' todos we'll add a comments feature so users can comment on todos. You'll see how to publish multiple cursors from one publish function, join data in a template, and use the momentjs package for formatting the timestamp.

* <a href="https://www.eventedmind.com/classes/build-a-multi-page-app-with-iron-meteor-6737880d/securing-the-publish-functions-b119bd63" target="_blank">Securing the Publish Functions</a> - It's a good idea to secure your publish functions independently of the views. Otherwise, anyone can open up a JavaScript console and subscribe to a publish function that's intended to be private. In this lesson we'll ensure that a user is logged in before publishing any data. We'll also take care to implement this feature in a way that's compatible with the spiderable server-side rendering package.



