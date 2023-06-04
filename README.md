# Intro to Coding for Busy People

## References
- https://www.youtube.com/watch?v=ysEN5RaKOlA
- https://www.theodinproject.com/paths

## Outline
* [ What is Web Development ](#what-is-web-development) ?
    - [ How websites work ](#how-websites-work) ?
    - [ Front-end and Back-end ](#front-end-and-back-end)
    - [ Code Editor ](#code-editor)

* [ Basic Front-end ](#basic-front-end)
    - [ HTML ](#html)
    - [ CSS ](#css)
    - [ JavaScript ](#javascript)

* [ Tools ](#tools)
    - [ Package Managers ](#package-managers)
    - [ Build Tools ](#build-tools)
    - [ Version Control ](#version-control)

* [ Additional Front-end ](#additional-front-end)
    - [ Sass ](#sass)
    - [ Reponsive Desgin ](#reponsive-desgin)
    - [ JavaScript Frameworks ](#javascript-frameworks)
* [ Basic Back-end ](#basic-back-end)
    - [ Server ](#server)
    - [ Programming Language ](#programming-language)
    - [ Database ](#database)
    - [ API ](#apis-application-programming-interfaces)

<!-- * Exercises
    - Watch
        - https://www.youtube.com/watch?v=ysEN5RaKOlA
    - Install VSCode
    - Install Git: follow the video
        - https://www.youtube.com/watch?v=8Dd7KRpKeaE
    - Create web page with a button. When clicked, a HELLO WORLD msg is shown
    - Build a Todo App:
        - front-end
        - back-end -->

## What is Web Development
 ### How websites work
- Websites are essentially a collection of files stored on a [ server ]()
    - ##### a server is just a machine connected to the Internet that serves things (e.g. files)
- You can load a website through a browser like Chrome, Firefox, or Safari, which acts as the client.
- The [ client ]() loads data from the server and also submits data back to the server, establishing a back-and-forth relationship.
    - #### client example = web browser
### Front-end and Back-end
- Front-end development mainly deals with the client-side of the website, focusing on what users see and experience in their browsers.
    - It involves creating the visual elements, layout, and interactivity using [ HTML ](), [ CSS ](), and [ JavaScript ]().
- Back-end development involves handling the server-side of the website, which users don't directly interact with.

### Code Editor
- You write code in it
- Just download `VSCode` for simplicity

## Basic Front-end
### HTML
- HTML (Hypertext Markup Language)  defines the structure and content of a webpage using tags and elements.
### CSS
- CSS (Cascading Style Sheets) is used to style and format the HTML elements on a webpage.
- It allows you to control the colors, layout, fonts, and overall appearance of a website.
- CSS works hand-in-hand with HTML to create visually appealing web pages.
### JavaScript
- JavaScript is a programming language that enables interactivity on a website.
- With JavaScript, you can add dynamic elements, create animations, handle user input, and perform complex operations on the client-side.

### Front-End Frameworks:
- [ Framework ]()
    - Imagine making ramen yourself. You have to make the noodles, the broth, the meat, the veggies, etc.
    - Instead, you buy a pack of ramen. All that are essential is ready, you just need to follow the instructions on the package, and you are free to add whatever you want to suit your taste.
    - You can say a pack of ramen itself is some sort of a framework, a framework for cooking ramen.
- Once you are used to HTML, CSS, JavaScript, you will notice that you will end up doing the same thing again and again.  Frameworks solve it by doing those things for you.
- For example, instead of having noodles, sauce, meat, prepared for you, front-end framework prepare components that handling browser compability, styling and theming, etc.
- e.g `React`, `Angular`, or `Vue.js`.

## Tools
### Package Managers
- You are making spaghetti, you need tomato sauce, grounded beef, pasta.
    - You do not need to make those ingredients yourself but you still have to go to the supermarket to fetch them.
    - And you have to keep tab on whether or not they are expired, etc
    - Imagine having a robot to do those things for you, that's your Package Manager.
- Like a dish depending on premade ingredients, your application will depend on third-party libraries and dependencies, Package Manager fetch, update and manage them for you
- e.g. `npm`, `yarn`

### Build Tools
- You are making sushi, you have everything ready, now you have to assemble everything into those sushi rolls. Imagine having a robot do it for you, again. That's your equivalent of a build tool
- e.g.  `grunt` and `gulp`, `webpack`, are used to automate repetitive tasks in the development process. They can help with tasks such as code minification, bundling, transpilation, and asset optimization.
### Version Control
- Imagine editting a document.
    - You will often want to save the Monday progress into a file, so that Tuesday when you mess up something, you can always go back.
    - Then Tuesday end, you want to save your progress, but not to overwrite Monday's save, just in case on Wednesday you want to discard Tuesday work and go back to where you were on Monday
    - After 1 month, the amount of save files you have to managed will be un-manageable
- Version control systems enable you to track changes in your codebase, collaborate with other developers, and easily revert back to previous versions if needed.
- e.g. `Git`
- GitHub and GitLab are popular platforms for hosting Git repositories and collaborating with others.
    - `Git repository`: simply it's a folder managed by Git

<!-- ## Additional Front-end
### Sass
- CSS preprocessors like Sass (Syntactically Awesome Style Sheets) and Less enable you to write CSS in a more efficient and maintainable way. They provide features like variables, mixins, nesting, and functions, which can simplify your CSS code and make it easier to manage stylesheets.
- CSS Frameworks: CSS frameworks such as Bootstrap, Foundation, and Bulma offer a collection of pre-designed CSS and JavaScript components that can speed up your development process. These frameworks provide a responsive grid system, ready-to-use UI components, and styling presets, allowing you to create attractive and consistent designs more quickly.
### Reponsive Desgin
- With the increasing variety of devices and screen sizes, it's crucial to create websites that adapt to different screen resolutions. Responsive web design allows you to build websites that respond and adjust their layout based on the screen size, providing a better user experience across desktops, tablets, and mobile devices. -->

## Basic Back-end

## Server
- the server is the computer where all website files the database and other components are stored
- traditional servers run on operating systems such as Linux or Windows

### Programming Language
- e.g. `JavaScript` and `TypeScript` with `node.js`, `PHP`, `Python`, `Ruby`, `C#`, `Java`
- These languages allow you to handle data, process requests, interact with databases, and perform other server-side tasks.
### Database
- You need a persistent place to store the data of your application, and that's the database.
    - *persistence* just means the data will not be erased if the users of your application turn off/clear his browser/computer, or if your server shutdown.
    - the data can be usernames, birthdays, etc.
- 2 types of database: [ SQL ](#reasons-for-sql) and [ NoSQL ](#reasons-for-nosql)
#### Reasons for SQL:
    - Structured data
    - Strict schema
    - Relational data
    - Need for complex joins
    - Transactions
    - Clear patterns for scaling
    - More established: developers, community, code, tools, etc
    - Lookups by index are very fast
    - e.g. `MySQL`, `PosgreSQL`, `NoSQL`
#### Reasons for NoSQL:
    - Semi-structured data
    - Dynamic or flexible schema
    - Non-relational data
    - No need for complex joins
    - Store many TB (or PB) of data
    - Very data intensive workload
    - Very high throughput for IOPS
    - .e.g. `MongoDB`, `Cassandra`, `Redis`
    - Sample data well-suited for NoSQL:
        - Rapid ingest of clickstream and log data
        - Leaderboard or scoring data
        - Temporary data, such as a shopping cart
        - Frequently accessed ('hot') tables
        - Metadata/lookup tables

### APIs (Application Programming Interfaces):
- Basically a API of a software system is an agreement of how other software systems should communicate with it.
- An example of API in the physical world is your USB port on your laptop.
    - It has a specific shape and size, etc. Any electronics wanting to connect with your laptop USB port need to respect this shape, size, voltage, etc.
- Another example is the way you communicate with your tax office.
    - You need to fill in specific forms that has many fields. Some field only accept a string of numbers (your income) instead of an alphabet string
- APIs allow different software systems to communicate and interact with each other.
- Back-end developers often build APIs to expose functionality and data from the server-side to be consumed by front-end applications or other third-party services.


<!-- ### Server Environment:
- Back-end developers work with server environments like Apache, Nginx, or Microsoft IIS, which handle the processing of requests and serve web pages to users. These environments also provide tools for managing server configurations, security, and performance optimization.

### More on Server
- they're considered centralized  because everything the website files back-end code and data are stored all together on the server
- nowadays there are also **serverless architectures** which is a more decentralized type of setup this  type of application splits up those components and leverages third-party vendors to handle each  of them
    - despite the name though you still do need some kind of webserver to at least store your website files
    - some examples of service providers are AWS Amazon Web Services
    - serverless set ups are popular because they are fast cheap and you don't need to worry about  server maintenance they're great for simple
- static websites that don't require a traditional  server-side language. However for very complex applications the traditional server setup might  be a better option


### Server-Side Frameworks:
- Server-side frameworks like Django (Python), Ruby on Rails (Ruby), Laravel (PHP), Spring (Java), or Express (Node.js) provide a structured way to develop web applications. These frameworks offer built-in functionalities, routing systems, database integration, and security features, which help speed up development.

<!-- ### Authentication and Authorization:
Back-end developers handle user authentication and authorization to secure web applications. Techniques like password hashing, session management, JSON Web Tokens (JWT), OAuth, and role-based access control are commonly used for user management and authorization.

### Web Security:
Back-end developers play a critical role in ensuring the security of web applications. They need to be familiar with security best practices, such as input validation, data sanitization, protection against cross-site scripting (XSS) and SQL injection attacks, and secure communication over HTTPS.

h. Caching and Performance Optimization: Back-end developers optimize the performance of web applications by implementing caching mechanisms, such as content caching, database query caching, or using caching services like Redis or Memcached. They also optimize server configurations and database queries to reduce response times.

i. Deployment and DevOps: Back-end developers are responsible for deploying web applications to production environments. Understanding deployment processes, version control systems like Git, continuous integration/continuous deployment (CI/CD) pipelines, and cloud platforms like AWS or Azure are important in modern back-end development.

j. Scalability and Load Balancing: As web applications grow, back-end developers need to design systems that can handle increased traffic and load. Concepts like horizontal scaling, load balancing, and distributed architectures help ensure the scalability and performance of web applications. -->

