

# Novice Level

At this level an interviewer wants to know whether the interviewee is a coachable self-learner. Hence, he/she might ask questions about 

basic terminology, your ability to build a simple app, and your comprehension of basic concepts.

Familiarity of Basic Terminology

What are the differences between AngularJS (angular 1.x) and Angular (Angular 2.x and beyond)?

What is a component? Why would you use it?

What is the minimum definition of a component?

What is a module, and what does it contain?

What is a service, and when will you use it?

What is a promise? Explain it laymen's terms.

What are the lifecycle hooks for components and directives?

What are pipes? Give me an example.

What are the differences between reactive forms and template driven forms?

What is a dumb, or presentation, component? What are the benefits of using dumb components?

Ability to Build Simple App

How do components communicate with each other?


How would you use http to load data from server?

How do you create routes?

How can you get the current state of a route?

How do you create two-way data binding?

How do you load external modules?

How would you display form validation errors?

Which lifecycle hook would you use to unsubscribe an observable?

How are services injected to your application?

How would you create route parameters and access them from a component?

Basic Concepts

Why would you use Angular instead of another framework, e.g., React?

What is the difference between an observable and a promise?

What is the difference between a component and a directive?

Why would you use typescript aka benefits of typescript?

Why different life cycle hooks are needed for a component/directive?

Why does angular use rxjs?

What is the purpose of using zone.js?

What is the difference between ngOnInit() and the constructor() of a component?

When will ngOnInit() be called? How would you make use of ngOnInit()?

What are the benefits of using formBuilder?

[Answers link coming soon ]

# Intermediate Level

To be in the intermediate level, you have to build at least one medium sized angular app. You have to have familiarity with routing, 
https, different built process, unit test, etc. here are the questions you could expect.

Essential Terminology Questions

How will you protect a route for authorized user only?

What is a custom pipe and how will you use it?

What is a structural directive?

What is the difference between RouterModule.forRoot() vs RouterModule.forChild()? Why is it important?

What is the difference between a module's forRoot() and forChild() methods and why do you need it?

What's the difference between dirty, touched, and pristine on a form element?

What is an async pipe? What kind of data can be used with async pipe?

What is injectable? Give me some example.

What is a pure pipe?

How will you create two-way data binding in Angular?

Comfortability to Build Medium Size App Questions

How do components communicate with each other?

How do you decide to create a new NgModule?

How will you inject custom header in your http call?

How do you identify a structural directive in html?

How would you select a custom component to style it?

How would you select all the child components' elements?

How would you cache an observable data?

How would you save data from a form control?

How Event Emitters works in Angular?

How do you mock a service to inject in a unit test?

Core Concepts Understandability Questions

Tell me about feature module and shared module?

What would you not put in a shared module?

Why angular uses decorator?

What is async validation and how is it done?

Why do you need type definitions?

Which components will be notified when an event is emitted?

Why would you export from ngModule?

Why is it bad if SharedModule provides a service to a lazy loaded module?

Can you explain the difference between ActivatedRoute and RouterState?

Which service will you put in the module and why?

[Answers link coming soon]

#  Expert Level

You are a Rockstar in angular. You can teach other. You can lead a team of angular developers.

Performance and Edge case Related Terminology
What is a factory Component?

What is lazy loading and why will you use it?

What is Ahead of time (AOT) compilation and why will you use it?

What are some of the Angular Style Guide suggestions you follow on your code? Why?

What is wildcard state?

How do you put animation between two states?

What would be a good use for NgZone service?

How would you protect a component being activated through the router?

How would you insert an embedded view from a prepared TemplateRef?

What is attribute directive and why will you use it?

Master a Large App

How will you intercept http to inject header to each http call?

How would you create a component to display error messages throughout your application?

How will you parallelize multiple observable call?

How will you put one async call before another?

How can you use web worker in angular app?

What tools would you use to find a performance issue in your code?

What are some ways you may improve your website's scrolling performance?

Explain the difference between layout, painting and compositing.

How can you cancel a router navigation?

How would you animate routing?

How would you cancel a promise on which you are waiting?

Rockstar and Fighter for Angular Questions

When does a lazy loaded module is loaded?

Why angular uses url segment?

How will you make angular app secure?

How will you localize numbers currencies and dates?

What is the best way to use translation in your app?

How will you setup different environment build differently for your app?

How will you use scss or css preprocessing with your application?


How will you optimize image/svg in your angular app?

How would you make sure an api call that needs to be called only once but with multiple conditions? Example: if you need to get some 
data in multiple routes but, once you get it, you can reuse it in the routes that needs it, therefor no need to make another call to 
your backend apis.

If you need to respond to two different Observable/Subject with one callback function, how would you do it? (ex: if you need to change the url through route parameters and with prev/next buttons).
[Answers link coming soon]

Coding Test

Sometimes interviewer gives real coding test. Most of us suck on those and feel ashamed of ourselves and then continue to work in the current job. I don't want you to saty in that miserable job. Hence, take the following coding challenges and master them.

Fetch Data and Display User Profile

This test has three level

Level 1: I am giving you an api https://api.github.com/search/users?q=eric This api takes a query parameter name "q" and passes query string to server. Server returns bunch of users. Now I want you to create a input text box and button so that you can type anything on the text box and hit on the button to retrieve data from the given api. Upon retrieval display total_count and first 10 users in the search result. Detail instruction about this test is available here

Level 2: Convert each user profile as a router link so that upon clicking on each user profile you will navigate to a route that has "login" property in the route. Pass user.login as route parameter. Create a separate component where you will read the route parameter and then fetch data for that user by using this api https://api.github.com/users/eric . Please Notice that last part of this api is the user.login (the route parameter that you have passed). Finally display user image and few other information in the component

Level 3: use any charting framework that you can find and then create a simple bar chart to display number of followers of first 10 users
This coding test will judge your ability to use services, component, routing, data visualization, external module, observables, etc.
[Sample code link coming soon]

# Persistent Todo List

This test has three levels

Level 1: Implement a simple todo list where you can add items, mark as done

Level 2: Now create few categories of todo list and make it persistence in the browser

Level 3: Now use firebase (serverless database) to make todo list persistence across multiple devices

This coding test will judge whether you can pass data and events between components. Also, whether you are leveraging directives and understand difference between component and directives.

[Sample code link coming soon]

Student Registration System

This test has three levels

Level-1: Design a system where students can login to register different courses

Level-2: Add a feature so that faculties on each course can view how many students registered on the courses

Level-3: (I need a shower. will add text here after I clean up myself)

This coding test will judge your understanding of architecture for a large application. Your ability to think and implement module, lazy loading, asset management etc.
[Sample code link coming soon]

Side Things Related Questions

# rxjs

Why unsubscribing is important?

What is the difference between map and flatmap?

Whare are the different ways you can create an Observable?

What is forkJoin, zip, share?

Difference between hot and cold observables.

#  TypeScript

How would you debug a typescript file?

How do you implement interface in typescript?

How would you call base class constructor from child class in typescript?

What is typescript language service?

How to declare a custom type?

what are some disadvantages of typescirpt? answers here

# angular-cli

Why would you use angular cli?

How would you run unit test?

How do you create application to use scss?

How to inject base href?

How would you extract webpack config from angular cli project?

# Others

What is the use of codelyzer?

Will you use Angular Material2?

How would you set different config in different deployment server?

What do you know about ES6?


What is ngUpgrage? Do you know how you can run angularJS and angular side by side?
