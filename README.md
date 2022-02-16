# QAChallenge

1. First download the zip file from the given Github url and save it into your local eclipse-workspace path.
2. Add the TestNG library in the downloaded project.
3. Then right click on the project and then click on TestNG->Convert to TestNG,then testng.xml file would get created.
4. Then delete all the classnames only keep the classname as <class name="aspire.qa.test.ManufacturingPageTest"/> in testng.xml file.
5. Then go to src/main/java and go to aspire.qa.properties and then click on config.properties and then right click on config.properties file,go to Properties and then copy the path and then paste the path of your local system whatever it is in aspire.java.base->TestBase.java file.
6. If you want to change the productname you can change it from config.properties file in productname as I have made productname as dynamic.
7. Then for exceution of the TestNG Suite,go to testng.xml and then right click on testng.xml file and then click on Run As-> TestNG Suite.Then in this way the entire TestNG suite will be executed and the given conditions would be met.
