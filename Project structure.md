Angular 4 Project Structure<br>

Open your cmd / terminal , Run it as an administrator and then simply type<br>

ng new my-first-app<br>

----------------------------------------------------------------------

1.) e2e<br>

As applications grow in size and complexity, it becomes unrealistic to rely on manual testing to verify the correctness of new features.<br>
End-to-end tests are made to find these problems.<br>
End to end testing (E2E) or also known as integration testing is a great way to make sure that our applications function correctly.<br>


app.po.ts : <br>

     a.) Protractor is a Node.js program, and runs end-to-end tests

     b.)  Protractor is used to control browsers and simulate user actions.

     c.) It uses Jasmine Framework as its syntax. (Jasmine is an open source testing framework for JavaScript)


app.e2e-specs.ts : <br>

      a.)  In unit testing, a test file is comprised of one or more it blocks that describe the requirements of your application.

      b.) it blocks are made of commands and expectations. <br>Commands tell Protractor to do something with the application such as navigate to a page or click on a button. 
      
      Expectations tell Protractor to assert something about the application's state, such as the value of a field or the current URL.

      c.) Test files may also have beforeEach and afterEach blocks, which will be run before or after each it block regardless of whether the block passes or fails.

--------------------------------------------------------------------------------------------------------------

TypeScript is a free and open-source programming language developed and maintained by Microsoft. It is a strict syntactical superset of JavaScript<br>

---------------------------------------------------------------------------------------------------------------

JSON: JavaScript Object Notation.<br>

JSON is a syntax for storing and exchanging data between a browser and a server.<br>

--------------------------------------------------------------------------------------------------------------


app-component <br>

Components are the most basic building block of an UI in an Angular application. An Angular application is a tree of Angular components.<br>


app-module <br>

In Angular, a module is a mechanism to group components<br>

--------------------------------------------------------------------------------------------------------------


assets <br>

assets can be used for putting stuff like images.<br>

--------------------------------------------------------------------------------------------------------------


