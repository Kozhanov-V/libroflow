# libroflow
## Installation & Running the App with maven 🏃‍♂️
1. Clone the repository from GitHub.
   ```
   git clone https://github.com/Kozhanov-V/Credit-Finance-Institution-Handbook.git
   ```
2. Configuring the application.properties file
``` spring.datasource.url=jdbc:postgresql://host:port/namedb
spring.datasource.username=username
spring.datasource.password=password 
```
### change host, port, namedb, username and password to yours values
3. Navigate into the project directory.
   ```
   cd Credit-Finance-Institution-Handbook
   ```
4. Build and run .
   ```
	mvn package
   ```
	 ```
	 cd target
	 ```
	 ```
	 java -jar library-management-1.0-SNAPSHOT.war
	 ```
   Now, you should be able to access the application at localhost:8080.