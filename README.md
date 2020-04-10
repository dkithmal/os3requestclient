This is a sample vaadin project configured to deploy to aws beanstalk

important informaiton
this project need to build in production mode (otherwise beanstalk will not work)
mvn clean package -Pproduction

running port set to 5000 in application.properties


