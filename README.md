# Product
This is a demo project to list the product.
### Project setup Prerequisites:
1. Git
2. Docker and Docker Comoose

Note: Docker and Docker Compose should have proper permission.

### Project setup guide:
1. Open the ternimal and clone the project.

    `git clone https://github.com/mohit-in/product.git`

3. Go to the project directory.

    `cd product`

3. Run the docker-compose up commnad to initilize the project.

    `docker-compose up`

4. open the browser and hit the app url. You will get the home page of your product app.

   `localhost:8700`

  Note: port 8700 should be free to use.


### Project some useful command and tips:
1. App Documnetation page

    `/api`

2. To run all the tests at a time(PHPUnit, PHPSpec, Behat, Code Quality tools(PHPStan and PHPCS)).

    `bin/console run:tests`

3. To run single type of test or single test. use the standard command of that particular test.
