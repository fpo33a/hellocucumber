https://cucumber.io/docs/guides/10-minute-tutorial/

Steps to achieve

1/ generate the project - it can be done via artyfact - see create-project.bat
   - you get pom.xml, RunCucumberTest.java & StepDefinitions.java in test (sub)folders

2/ create your feature file in test resources folder
   - enter feature & scenario

3/ run "mvn test" - it will fail but in the output it gives you the squeleton of the code to add in StepDefinitions.java

4/ re run "mvn test" - it still fail as squeleton doesn't provide any business implementation ( throw pending exception )

5/ put your business logic in the StepDefinitions.java / squeleton functions

6/ run the tests  