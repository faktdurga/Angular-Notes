# Angular-Notes
**Section 1 : Introduction**
Angular is used to create single page application. Single page applicaiton means on browser only serves one page and then content is loaded dynamically based on user interaction without changing URL.
Initially is it released Angular Js (Angular 1) which is based on javascript then Angular 2 onwards it is based on typesript. 

**Creating New Angular Project**
1.  Download Node.js and install it
2.  Open Command prompt and execute 'npm install -g @angular/cli' command
3.  Then go into respective directory and run command 'ng new first-angular-app '


**Section 2 : Angular Essential**
Understanding Angular Structure
1. Configuration files
   1. Type script configuration files tsconfig.json, tsconfig.app.json, tsconfig.spec.json related to typescript 
   2. package.json and pachakge-lock.json contains packages related configuration which application is going to use
   3. angular.json file contains extra configuration related to angular cli and angular provided tools in general
2. SRC
   1. This is place where actual work happens  it contains app folder which consits 4 components files that is
      app.component.ts - typescript file where actual business logic is written
      app.component.spec.ts - used for unit testing
      app.component.html - html template code
      app.component.css - style part for component's html file
   2. Index.html - this file loaded into browser when request for page. It contains the <app-root></app-root> element which is not html standard element
   3. Main.ts - this file is first typescript code that executed automatically at backend which bootstrap app.component  

Working with Components
Component is important part when ever any content loaded on browser component file is responsible for importing it. Components consist of three part mainly 
1. Import section where we can import required dependencies
2. Decorator : - Decorator contains information of metadata that is responsible for treating normal class as component using @Component decorator.
3. class : - basically component is nothing but the class that contains some logic based on that respective template works.

Handling User Events
Rendering and Updating Dynamic UI Content


