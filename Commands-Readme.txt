Backend Commands:

* To build your project use command:
	mvn clean package -Dmaven.test.skip

* To launch your application, move into the target folder (cd target). Run the following command to run the application:

	java -jar <your application jar file name>

* Default credentials for MySQL:
	Username: root
	Password: pass@word1

* To login to mysql instance: Open new terminal and use following command:
      a.	sudo systemctl enable mysql
      b.	sudo systemctl start mysql
      NOTE: After typing the second sql command (sudo systemctl start mysql), you may encounter a warning message like:
	System has not been booted with systemd as init system (PID 1). Can't operate.
	Failed to connect to bus: Host is down
      --> Please note that this warning is expected and can be disregarded. Proceed to the next step.
      c.	mysql -u root -p
The last command will ask for password which is ‘pass@word1’

* Mandatory: Before final submission run the following command: 
	mvn test

* To ensure your code is saved and available for later use, remember to use the CTRL+Shift+B command on your code IDE.
   This will push or save the updated contents in the internal git/repository.
   It is also important to use CTRL+Shift+B before the final submission to evaluate the code quality.


Frontend Commands:

* You can follow series of command to setup Angular environment once you are in your project-name folder:

	npm install -> Will install all dependencies -> takes 10 to 15 min
	npm run start -> To compile and deploy the project in browser. -> takes 2 to 3 min and will run on localhost:8082
        npm run jest -> to run all test cases and see the summary
	npm run test -> to run all test cases. It is mandatory to run this command before submission of workspace -> takes 5 to 6 min
* To ensure your code is saved and available for later use, remember to use the CTRL+Shift+B command on your code IDE.
   This will push or save the updated contents in the internal git/repository.
   It is also important to use CTRL+Shift+B before the final submission to evaluate the code quality.
