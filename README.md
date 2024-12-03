### Steps to Build and Run
Create the App Directory Structure

Place the Dockerfile and index.php inside a folder named php-app.
Place the docker-compose.yml in the root of the project.
Build and Start the Containers Run the following command in the project folder:

```bash
   docker-compose up --build
```
Access the PHP App

Open your browser or use curl to navigate to http://localhost:8080.
You should see the message:
```css
Connected to MySQL successfully!
```
Check the MySQL Database

Use a MySQL client or a tool like MySQL Workbench to connect to the MySQL server at localhost:3306 with the username root and password root.
This setup connects a PHP app to a MySQL database via Docker Compose, ensuring the services start in the correct order and persist data across container restarts.