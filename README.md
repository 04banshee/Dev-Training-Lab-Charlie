# Dev Lab CHARLIE/486 Story Card 

## User Story (Story Points = med👕) 

**As a** user of a NodeJs application.

**I want** to interact and respond to the NodeJs app by providing input and have the appliction respond to user input. 

**So That** the application is dynamic and interactive [like this one](https://dev-training-lab-charlie.herokuapp.com/) to the end user.

## Comments/Discussion
#### AngularJs Background
- AngularJs is ideal for creating dynamic web applications.  To better understand Angular [click here](https://docs.angularjs.org/guide/introduction) and check out what it has to offer.
- Angular uses `end points` to bind information to `call back`functions.  The data in the `end points` bind to a call back function and displays to a web browser .  Below is an example of this in `action`.

```AngularJs
 $http.get('/user')
      .then(response => {
          console.log(response.data);
          $scope.user = response.data;
       });
```
The `end point` in the example is /user.  Angular uses the data from the "user" file, which is a .json file.  AngularJs binds the contents of the file to the `call back` function and displays the data **asynchronously** to the web browser.  A input bock can be included so a user can dynamicly interact with the app.  [See it in action](https://dev-training-lab-charlie.herokuapp.com/) here.  Instead of sending the entirer webpage back to the server `AngularJs` is only sending the input the user types.  


## Resources
  ### Packages:
  - [AJAX](https://ajax.googleapis.com/ajax/libs/angularjs/1.5.6/angular.min.js)
  - [JQuery](https://code.jquery.com/jquery-3.3.1.min.js)
  - [BootStrap](https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js)
-  There are many tutorials that will aid in Angular development, [this is one is good](https://www.tutorialspoint.com/angularjs/angularjs_overview.htm) 👍  
-  Angular uses JSON files to read data from. If you are unfamiliar with JSON file format [check out this out](https://docs.fileformat.com/web/json/).
-  To aid in Angular development the Chrome web browser has an web extension for [checking](https://chrome.google.com/webstore/detail/jsonview/chklaanhfefbnpoihckbnefhakgolnmc) JSON files.  

## Test/Acceptance Criteria/Rubric (how do you know when you are done) 

- [ ] Navigate to a URL: _______ (heroku): 0 | 5 | 10
- [ ] App has a  link back to ghyt repo w/target: 0 | 5 | 10
- [ ] File directory and naming, ghyt link to heroku: 0 | 5 | 10 
- [ ] Readme: explain some about angular...how user types in input and where that data goes from there, use code hightlight syntax in markdown: 0 | 5 | 10 
- [ ] Code quality: logical, readable, functional: functional = loads user json data, changes input data; updates a file on the server0 | 5 | 10  
