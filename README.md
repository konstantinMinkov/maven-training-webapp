# maven-training-webapp

1. Create project with exec plugin. Main class should work with parameters. 
Write command examples for maven to run project. Create build profile that will turn on exec plugin. 
Use property to specify main class.

  $> mvn clean install -P exec-profile

2. Create project with 2 types of test - ITest and simple test. 
Configure maven to run build without ITests. 
Create profile to run build with ITests, only ITests. 
Use maven properties to configure ITest name convention.

3. Create project with sql data. Use Flyway* or liquibase plugin to populate dbdata 

4. Create project with some plugins that you think are useful for your lbs project. 
