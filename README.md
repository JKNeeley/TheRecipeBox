# GlobalRecipeBook
© 2024 ???. All rights reserved.  Unauthorized copying, distribution, or modification of the content on this website is strictly prohibited. Any attempt to reproduce, distribute, or modify the content may result in legal action, including take-down notices, cease and desist orders, and litigation.
## Project Premise
???aims to revolutionize the way users interact with recipes by providing a comprehensive platform where they can create, discover, and manage their culinary creations. ??? simplifies the recipe management process by offering features such as manual recipe entry, URL-based recipe import, and advanced search functionalities. Additionally, users will have access to features like user profiles, ratings, reviews, and social sharing functionalities, enhancing the cooking experience and fostering a sense of community among users of all skill levels.
## Mission Statement
Empower individuals to explore their passion for cooking by providing them with a user-friendly platform to create, discover, and share recipes effortlessly.
##About the Developer
??? is developed by Jade Neeley, a passionate individual with a love for food and technology. She has expertise in Java, Spring, React, and Tailwind CSS during her time as a Software Engineer for Shelter Insurance. She plans to create a seamless and enjoyable user experience utilizing these technologies.
## Introduction
### Problem Definition
In today's fast-paced world, cooking has transcended its traditional role as a mere necessity; it's now a form of self-expression and creativity. However, managing recipes can often feel overwhelming, given the multitude of online resources available. ???  aims to simplify this process by providing a centralized platform where users can effortlessly access, create, and organize recipes.
Existing recipe management solutions lack comprehensive features and often demand manual effort to input or import recipes. Users are struggling to find a platform that seamlessly combines intuitive design with advanced functionality, resulting in a fragmented cooking experience.
### The Solution
??? provides a comprehensive solution for all recipe management needs. With features such as manual recipe entry, URL-based recipe import, and advanced search capabilities, our platform simplifies the process of discovering, organizing, and sharing recipes.
### Solution Benefits
??? offers a plethora of benefits aimed at enhancing the recipe management experience for users. Firstly, by streamlining the process of creating, discovering, and organizing recipes, our platform simplifies the often-cumbersome task of managing culinary creations. With its intuitive design and advanced functionality, users can easily input their own recipes manually or import them from external sources via URL, thereby expanding their recipe catalog effortlessly.
Additionally, ??? provides advanced search capabilities, allowing users to filter recipes based on various criteria such as cuisine, dietary restrictions, cooking time, and more. This enables personalized recipe discovery tailored to individual preferences. Moreover, the platform's recipe details page offers comprehensive information, including ingredients, instructions, cooking time, servings, and nutritional information, empowering users with all the necessary details to recreate their favorite dishes with confidence.
Furthermore, ??? facilitates user engagement and organization by enabling users to save recipes to their favorites. Overall, our platform revolutionizes the cooking experience by providing a centralized destination that combines convenience, functionality, and accessibility, catering to culinary enthusiasts of all skill levels.
## Requirements
### System/Hardware Requirements
•	Web Browser: Specify compatible web browsers for optimal performance. Consider popular browsers like Google Chrome, Mozilla Firefox, Safari, and Microsoft Edge.
•	Stable Internet: Mention minimum internet speed requirements for seamless usage, especially for uploading and downloading recipes.
### User/Functional Requirements
•	Ability to create recipes manually: Include features such as adding ingredients, instructions, cooking time, difficulty level, and optional images.
•	Ability to import recipes from blog posts: Clarify supported formats (e.g., JSON, XML, etc.) and provide guidelines for importing recipes from external sources.
•	Advanced search functionality: Specify search filters like ingredients, cuisine type, dietary restrictions, cooking time, and user ratings.
•	Recommended recipes on the home page: Implement algorithms for personalized recommendations based on user preferences and browsing history.
•	Recipe details page: Ensure comprehensive details including nutritional information, video tutorials (if available), and related recipes.
•	User authentication and profile management: Include features like registration, login, password recovery, and profile customization.
•	Ability to save recipes to favorites: Allow users to bookmark/save recipes for easy access in their profile.
•	Responsive user interface: Ensure the website is mobile-friendly and adapts seamlessly to various screen sizes.
### Non-User/Non-Functional Requirements
•	Secure data storage and transmission: Implement encryption techniques, secure APIs, and HTTPS protocol for data protection.
•	Scalable architecture: Design the system to handle increased traffic and data volume. Consider cloud-based solutions like AWS, Azure, or Google Cloud.
•	High performance and responsiveness: Optimize website loading speed and minimize latency for better user experience.
•	Cross-browser compatibility: Test the website on multiple browsers to ensure consistency and functionality across platforms.
•	Compliance with web accessibility standards: Follow WCAG guidelines for making the website accessible to users with disabilities.
### Additional Considerations
•	Community features: Integrate features like comments, ratings, and user-generated content to enhance user engagement.
•	Social media integration: Allow users to share recipes on social platforms and facilitate social login options.
•	Monetization options: Explore revenue streams such as advertisements, premium subscriptions for exclusive content, or affiliate marketing with kitchenware brands.
•	Feedback mechanism: Implement a feedback system to gather user suggestions and improve the platform iteratively.
## Project Specifications
### General Information
#### Development Stack
To realize the vision of ??? and ensure a seamless user experience, the development environment will be structured around robust tools and technologies across the backend, frontend, and database layers. Leveraging the expertise in Java, Spring, React, and Tailwind CSS, the following stack and tools have been carefully selected:
##### Backend Development:
Java and Spring Boot will serve as the foundation for backend development, providing a robust and scalable environment for building RESTful APIs and managing business logic.
IntelliJ IDEA will be the Integrated Development Environment (IDE) of choice for its comprehensive features and support for Java development.
MySQL will be utilized as the relational database management system, ensuring efficient storage and retrieval of recipe data, user profiles, and related information.
##### Frontend Development:
React.js, coupled with Tailwind CSS, will power the frontend, enabling dynamic and responsive user interactions with elegant UI components.
IntelliJ IDEA will also cater to frontend development needs, providing seamless integration and support for React.js projects.
Node.js, npm/yarn, and Create React App will be instrumental in setting up the frontend development environment, managing dependencies, and bootstrapping React projects.
##### Database Development:
MySQL will be employed as the primary database system, offering reliability and performance for storing recipe data, user profiles, and associated entities.
MySQL Workbench will aid in managing and visualizing database schemas, facilitating efficient development and testing of database interactions.
#### Tools
##### Version Control
Git, in conjunction with platforms like GitHub or GitLab, will be utilized for version control, allowing for collaborative development, code management, and tracking of project changes.
##### Containerization
Docker will streamline the deployment process by containerizing application components, ensuring consistency across development, testing, and production environments.
##### Hosting Details
The application will be hosted on the cloud platform Heroku, ensuring scalability, reliability, and accessibility to users across different devices and locations.
##### API Documentation
Springfox will be employed for documenting RESTful APIs, providing clear documentation and facilitating communication between backend and frontend developers.
##### Testing
JUnit for backend testing and Jest for frontend testing will enable the implementation of automated tests, ensuring the reliability and stability of the application across different layers.
##### Continuous Integration/Continuous Deployment (CI/CD)
CI/CD pipelines, configured using GitHub Actions, will automate the process of building, testing, and deploying the application, facilitating rapid iteration and delivery of new features.
### System Architecture
#### Client-Server Model
##### Presentation Tier (Client)
•	Developed using React.js for dynamic and responsive user interactions.
•	Utilizes Tailwind CSS for styling and layout.
•	Handles user interactions, displays data, and sends requests to the backend.
•	Utilizes React.js components to create a dynamic and responsive user interface.
•	Makes AJAX requests to the backend API to fetch or update data.
##### Application Tier (Server)
•	Built using Java with the Spring Boot framework to handle HTTP requests and manage business logic.
•	Implements RESTful API endpoints to communicate with the client.
•	Receives requests from the client, processes them, and interacts with the database.
•	Implements business logic, authentication, authorization, and validation.
•	Provides RESTful API endpoints to perform CRUD operations on recipe data, user profiles, etc.
•	Utilizes Spring Boot features such as dependency injection, MVC pattern, security, and data access layers.
##### Client-Server Communication
•	The client communicates with the server through HTTP requests sent to the RESTful API endpoints.
•	Requests include operations such as creating recipes, retrieving recipe data, managing user profiles, etc.
•	The server processes these requests, interacts with the database, and sends back appropriate responses to the client.
##### Data Tier (Database)
•	Utilizes a relational database management system (RDBMS) like MySQL or PostgreSQL to store recipe data, user profiles, favorites, etc.
•	The database can be hosted either locally or on a cloud platform like AWS RDS or Google Cloud SQL.
•	Stores structured data related to recipes, user profiles, favorites, etc.
•	Follows a relational model with tables, rows, and relationships.
•	Designed to optimize queries for efficient data retrieval and manipulation.
#### Graph
#### Advantages
•	Each tier can be scaled independently based on demand. For example, the backend can be scaled horizontally by adding more server instances, and the database can be scaled vertically by upgrading hardware or using sharding techniques.
•	Separation of concerns allows for easier maintenance, testing, and updates. Changes to one tier do not necessarily impact the others.
•	Centralized server-side logic enables enforcement of security measures such as authentication, authorization, input validation, and data encryption.
•	Efficient client-server communication and optimized database queries contribute to overall system performance and responsiveness.
### Algorithms/API’s
#### Security
- OAuth 2.0/OpenID Connect: OAuth 2.0 is a widely adopted authorization framework that allows users to grant third-party applications limited access to their resources without sharing their credentials. OpenID Connect (OIDC) is an authentication layer built on top of OAuth 2.0, providing additional features for authentication. Integrate with OAuth 2.0/OIDC providers like Google, Facebook, GitHub, or enterprise identity providers.
- HTTPS Protocol: Encrypt communication between clients and servers using HTTPS to prevent eavesdropping and man-in-the-middle attacks. Obtain SSL certificates from Certificate Authorities like Let's Encrypt or commercial providers.
- Rate Limiting and Brute-Force Protection: Implement rate-limiting mechanisms to prevent brute-force attacks on login endpoints. Tools like Spring Security's rate-limiting features or middleware such as Express Rate Limit can help mitigate these risks.
- Cross-Site Scripting (XSS) and Cross-Site Request Forgery (CSRF) Protection: Employ techniques like input validation, output encoding, and CSRF tokens to mitigate XSS and CSRF attacks. Frameworks like React have built-in protections against XSS through JSX escaping.
#### Parsing Recipe Information from Web Pages
- HTML Parsing Algorithms: Utilize libraries like Jsoup to parse HTML content and extract relevant recipe information based on HTML structure, tags, and attributes.
- Natural Language Processing (NLP) Algorithms: Apply NLP techniques like Named Entity Recognition (NER) and part-of-speech tagging to identify and extract recipe components such as ingredients, instructions, cooking time, servings, etc., from textual content.
- Machine Learning Algorithms: Train machine learning models to recognize patterns in recipe web pages and extract structured data. Techniques such as supervised learning with labeled data or unsupervised learning for clustering similar content can be employed.
#### Implementing Search Functionalities
- Keyword Matching Algorithms: Implement simple keyword-based search algorithms to match user queries with recipe titles, ingredients, or tags.
- TF-IDF (Term Frequency-Inverse Document Frequency): Calculate the TF-IDF scores for words in recipes to determine their relevance to user queries. This algorithm helps prioritize search results based on the frequency of terms in recipes compared to their occurrence across the entire recipe database.
- Vector Space Model: Represent recipes and user queries as vectors in a high-dimensional space and calculate similarities using techniques like cosine similarity. This allows for more nuanced matching beyond simple keyword matching.
- Latent Semantic Indexing (LSI): Apply LSI to identify latent topics within recipe data and improve search accuracy by considering semantic similarities between queries and recipes.
#### Recommendation Systems
- Collaborative Filtering: Implement collaborative filtering algorithms such as user-based or item-based recommendation systems to suggest recipes based on user preferences and behavior. This approach leverages similarities between users or recipes to generate personalized recommendations.
- Content-Based Filtering: Analyze recipe attributes such as ingredients, cuisine, cooking time, etc., to recommend similar recipes based on content similarity. This approach is useful for suggesting recipes based on user preferences and past interactions.
- Hybrid Recommendation Systems: Combine collaborative filtering and content-based filtering approaches to leverage the strengths of both methods and provide more accurate and diverse recommendations.
- Matrix Factorization Techniques: Use matrix factorization methods like Singular Value Decomposition (SVD) or Alternating Least Squares (ALS) to decompose user-item interaction matrices and uncover latent factors driving user preferences.
### Data Storage
#### Data Model
##### User
- Name	Data Type	Nullability	Notes
- UserID	Integer	False	Unique
- Username	String	False	Unique
- Password	String	False	Needs to be encrypted or hashed
- Email	String	True	Unique
- Picture	String	True	Path to picture
- Allergies	List<String>	True	Automatic filter for feed/search
##### Recipe
- Name	Data Type	Nullability	Notes
- RecipeID	Integer	False	Unique
- Name	String	False	
- Description	String	True	
- Servings	Double	True	
- Cook Time	Time	True	
- Tags	List<String>	True	
- Pictures	List<String>	True	List of picture paths
- Ingredients	List<Ingredient>	False	
- Instructions	String	False	
##### Ingredient
- Name	Data Type	Nullability	Notes
- Name	String	False	Includes special instructions here 
- Quantity	Double	False	Default to 1
- Unit	String	True	
#### ER Diagram
<img width="468" alt="image" src="https://github.com/JKNeeley/GlobalRecipeBook/assets/65043370/9c35f335-8df6-4f99-8ed0-23c831c21bc7">
### User Interface
#### Use Case Diagram
<img width="289" alt="image" src="https://github.com/JKNeeley/GlobalRecipeBook/assets/65043370/97e9cae6-b1f7-4fd5-8edb-2169fe53faf2">
#### Website Flow
<img width="468" alt="image" src="https://github.com/JKNeeley/GlobalRecipeBook/assets/65043370/c289cb8f-79e6-44d0-9f15-0b0ade608b74">
#### Decision Diagram
<img width="468" alt="image" src="https://github.com/JKNeeley/GlobalRecipeBook/assets/65043370/6557ab63-5806-4d65-9c95-2659ddc099c3">
#### Wireframes
<img width="307" alt="image" src="https://github.com/JKNeeley/GlobalRecipeBook/assets/65043370/b576f222-47e2-4ef9-b377-832ceb7c082e">
<img width="307" alt="image" src="https://github.com/JKNeeley/GlobalRecipeBook/assets/65043370/51535904-a774-4e16-a04a-b838ec22a788">
<img width="307" alt="image" src="https://github.com/JKNeeley/GlobalRecipeBook/assets/65043370/3ac70f81-4d0b-4c26-a0ac-b2002c8302f1">
<img width="307" alt="image" src="https://github.com/JKNeeley/GlobalRecipeBook/assets/65043370/ef48a787-bf0a-4852-8d00-cce3bfc6c5fb">
<img width="307" alt="image" src="https://github.com/JKNeeley/GlobalRecipeBook/assets/65043370/e2f5a0cd-38d0-4856-890f-f5aacc40bdf4">
### Code Organization
## Branding
### Fonts 
### Colors 
### Logo 
## Development Plan
### Strategy
Agile is a software development methodology that emphasizes iterative development, collaboration, and flexibility in response to changing requirements. By embracing Agile principles as a solo developer, the developer can effectively manage the project, adapt to changing requirements, and deliver a high-quality product that meets the needs of the users.
The project will be broken down into small manageable tasks or user stories that will be worked on one iteration at a time, completing and testing each feature before moving on to the next. Tasks will be prioritized and re-prioritized regularly based on new insights, challenges, impact, dependency, and value before being broken into sprints. Each sprint will typically span 2-4 weeks, depending on the developer’s availability and the complexity of tasks. Goals will be set for each sprint to encourage progress and completion of tasks.
The developer will regularly review progress and the functionality that has been implemented by seeking feedback from peers, mentors, and online communities. Documentation will be updated regularly and will include project plans, code comments, and any decisions or changes made along the way.
### Environment
#### Backend Development 
IDE (Integrated Development Environment): IntelliJ IDEA offers features like code completion, debugging tools, and project management utilities that will streamline the backend development process.
Java Development Kit (JDK): Install the latest version of JDK compatible with IntelliJ and make sure to set up the IDE to use this JDK for compiling and running the Java code.
Spring Boot: Set up the development environment to work with Spring Boot, which simplifies the process of building Java applications. Use Spring Initializer or the IDE's built-in tools to create a new Spring Boot project.
Database Management System: Install a database management system (e.g., MySQL, PostgreSQL) locally for developing and testing the application's database interactions. Use tools like MySQL Workbench or pgAdmin for managing the databases.
API Documentation Tools: Use tools like Swagger or Springfox to document the RESTful APIs. This will help keep development on track of the API endpoints and facilitate communication with frontend developers.
#### Frontend Development 
Text Editor/IDE: IntelliJ IDEA with appropriate plugins for React development.
Node.js and npm/yarn: Install Node.js to run JavaScript on the server side and npm (Node Package Manager) or yarn for managing JavaScript dependencies. These are essential for building and running React applications.
Create React App: Use Create React App to bootstrap the React project quickly. This tool provides a pre-configured development environment with features like hot module reloading, JSX support, and optimized production builds.
Tailwind CSS: Integrate Tailwind CSS into the React project to easily create responsive and customizable UI components. Install Tailwind CSS using npm or yarn and configure it according to the project's requirements.
Version Control
Set up a version control system (e.g., Git) to manage the project's source code. Use platforms like GitHub or GitLab to host the repository and collaborate with others (if needed). Make sure to commit the changes regularly and follow best practices for branching, merging, and code reviews.
#### Testing
Integrate testing frameworks (e.g., JUnit for Java, Jest for React) into the development environment to write and run automated tests for the backend and frontend code. Consider implementing unit tests, integration tests, and end-to-end tests to ensure the reliability and stability of the application.
#### Continuous Integration/Continuous Deployment (CI/CD)
Set up CI/CD pipelines using tools like Jenkins, Travis CI, or GitHub Actions to automate the process of building, testing, and deploying the application. This will streamline the development workflow and ensure consistent delivery of new features and updates.
#### Documentation
Document the development environment setup, project structure, coding standards, and any other relevant information to facilitate onboarding and collaboration with other developers (if applicable) and to serve as a reference for theself.
### Timeline
#### Sprint 1: Initial Setup and Backend Development
•	Set up development environment (IDE, Git repository, project structure).
•	Create Spring Boot project with necessary dependencies.
•	Design database schema for recipes, users, and related entities.
•	Implement user authentication and registration functionality.
•	Set up basic RESTful API endpoints for CRUD operations on users and recipes.
•	Write unit tests for backend functionality.
•	Implement basic error handling and validation.
#### Sprint 2: Recipe Management Functionality
•	Implement manual recipe entry functionality (create, read, update, delete).
•	Develop recipe details page with ingredients, instructions, cooking time, servings, etc.
•	Add image upload functionality for recipes.
•	Implement favorite recipes feature for users.
•	Design and implement API endpoints for recipe management.
•	Write unit tests for recipe-related functionality.
•	Ensure proper error handling and validation.
#### Sprint 3: External Recipe Import and Search Functionality
•	Develop import recipe page for users to input URLs and extract recipe information.
•	Implement parsing logic to extract relevant information from blog posts.
•	Allow users to review and edit imported recipe information before saving.
•	Design and implement advanced search functionality with filters (cuisine, dietary restrictions, cooking time, etc.).
•	Update frontend to display search results and imported recipes.
•	Write unit tests for import and search functionality.
•	Test and debug integration between frontend and backend.
#### Sprint 4: User Profile and Social Features
•	Create user profile page with options to view and edit saved recipes, favorites, and shopping lists.
•	Implement social features such as following other users and sharing recipes.
•	Design and implement API endpoints for user profile management and social interactions.
•	Update frontend to display user profile information and social features.
•	Write unit tests for user profile and social features.
•	Test and debug integration between frontend and backend.
•	Ensure proper error handling and validation.
#### Sprint 5: UI/UX Improvements and Testing
•	Conduct UI/UX review and make improvements based on feedback.
•	Enhance styling and layout using Tailwind CSS.
•	Optimize frontend performance and responsiveness across devices.
•	Conduct user acceptance testing (UAT) to gather feedback and identify issues.
•	Address any bugs or usability issues reported during testing.
•	Write end-to-end (E2E) tests to ensure full application functionality.
•	Prepare documentation and user guides for deployment.
#### Sprint 6: Deployment and Finalization
•	Deploy application to production environment (AWS, Heroku, etc.).
•	Configure continuous integration/continuous deployment (CI/CD) pipeline if applicable.
•	Set up monitoring and logging to track application performance and errors.
•	Perform final round of testing in production environment.
•	Address any last-minute issues or bugs.
•	Launch and announce the application to users.
•	Gather feedback from initial users and plan future enhancements.
### Contingency Planning
#### Technical Challenges
Risk: Technical issues such as bugs, compatibility issues, or performance bottlenecks may arise during development.
Contingency Plan: Conduct thorough testing at each stage of development, including unit testing, integration testing, and user acceptance testing. Allocate time and resources for troubleshooting and resolving technical issues promptly. Utilize monitoring tools to detect and address performance issues proactively.
#### Resource Constraints
Risk: Limited availability of skilled developers, hardware resources, or budget constraints may impact project progress.
Contingency Plan: Maintain open communication with team members to identify any resource constraints early. Consider outsourcing certain tasks or adjusting project timelines to accommodate resource limitations. Explore alternative funding sources or cost-saving measures if budget constraints arise.
#### Scope Creep
Risk: Uncontrolled expansion of project scope may result in delays, budget overruns, and quality issues.
Contingency Plan: Establish clear project scope and objectives from the outset and document any changes through a formal change control process. Prioritize features and functionalities based on their importance and feasibility. Regularly review project scope with stakeholders to ensure alignment and manage expectations effectively.
Data Security and Privacy Concerns
Risk: Data breaches, unauthorized access, or non-compliance with data privacy regulations could lead to reputational damage and legal consequences.
Contingency Plan: Implement robust security measures, such as encryption, access controls, and regular security audits, to safeguard sensitive data. Stay informed about relevant data protection laws and regulations, such as GDPR or CCPA, and ensure compliance throughout the development process. Develop a response plan for handling security incidents, including communication protocols and notification procedures.
#### Dependency Risks
Risk: Dependencies on third-party libraries, APIs, or external services may introduce vulnerabilities or disrupt project timelines.
Contingency Plan: Conduct thorough due diligence on third-party dependencies before integration, including security assessments and compatibility checks. Have contingency plans in place for alternative solutions or fallback mechanisms in case of dependency failures. Monitor dependencies regularly for updates and vulnerabilities and implement patches or upgrades as needed.
## Future Development
### Day Two
#### Profile Improvements
-	User status
#### Recipe Improvements
-	Source of a recipe
-	Nutrition information within a recipe
#### Search Improvements
-	Filters for source and nutrition
#### Recipe Book Addition
-	Categories (sets of a user’s recipes)
-	Recipe books (collections of sets of a user’s recipes)
#### Community Addition
-	Friends system
-	Friend posts on feed
-	Posting newly created recipes
-	Posting about using pre-existing recipes
#### Mobile Compatibility
-	Cleaner usability for mobile users
### Day Three
#### Profile Improvements
-	Badges/achievements
#### Recipe Improvements
-	Ingredient substitutions within a recipe
-	Unit conversions within a recipe
#### Search Improvements
-	Filters for ratings and price
#### Recipe Book Improvements
-	For-sale recipes/recipe books
-	Recipe/recipe book ads on feed
-	Collaborative recipe books
-	Custom sections
#### Community Improvements
-	Linking posted photos to the recipe used
-	Ratings for recipes
-	Comments/likes 
#### Meal Planning Addition
-	Calendar meal planning
-	Grocery list creation
-	Calorie/nutrition recommendations
#### Mobile Compatibility
-	iOS/other application
