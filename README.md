Tests the 5 day weather forecast application at https://github.com/buildit/acceptance-testing using BDD with JavaScript in Gherkin.

### Exception scenarios covered
* Enter the city name ,which does not exist
* Enter the days which is not present in the application.

### Bdd scenarios and step_definitions are implemented in the files.
./features
./step_definitions

### Running the tests - locally

Pre-requisites - Install node and npm. 

To install dependencies:

    $ npm install

To start up the application:

    $ npm run develop

To execute the feature file
  
    $ npm test

### Reports can be found in
./reports

### Improvements
	Tests could be Dockerized given more time
