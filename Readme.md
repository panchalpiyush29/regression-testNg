## Run test on firefox browser from command line ##

mvn clean verify -Dwebdriver.gecko.driver=/Users/piyushpanchal/geckodriver

Note: For executing test on different browser's just change the path pointing to the correct browser file

## Run multiple threads ##

mvn clean verify -Dthreads=2 -Dwebdriver.gecko.driver=/Users/piyushpanchal/chromedriver4
mvn clean verify (everything else i.e. browser, threads via POM file)

## Run TeamCity via docker ##

Once you create a image (use the cool kitematic interface)
navigate to http://localhost:8111

Note Docker may give you a different access url check kitematic interface for the same and modify to run on 8111 port

