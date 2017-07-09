# mvn-repo
Maven repository for our private jars


see   https://cemerick.com/2010/08/24/hosting-maven-repos-on-github/

Usage:

cd liquibase
mvn -DaltDeploymentRepository=snapshot-repo::default::file:../mvn-repo/ clean deploy

this builds the project and deploys jar and other files to mvn-repo

