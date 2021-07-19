## Academic Store - API

This is a Store Backend API available only for Academic Purposes.
Feel free to download and use it to enhance your frontend development skills in any programming language and framework, such as Node.JS, JavaScript, Swift, Dart, C#, Python, etc. It is the beauty of the RESTFul API, wide compatibility.

### How to install locally

1. #### Install Docker

Academic Store API uses containers to run. So, it needs Docker Engine and Docker Compose installed. Both are included in Docker for Mac and Docker for Windows.
* Follow the installation guide for your operating system: https://docs.docker.com/engine/installation/

Note: On Windows you might need to re-start after the docker install to ensure the %path% is set correctly to docker which is by default: C:\Program Files\Docker\Docker\Resources\bin
   

2. #### Download docker compose file

Please clone or download this repository (on the green button called "Code", on the top). You can place it in any folder, but keep in mind you will need it to install, stop, and restart the containers.

3. #### Run docker compose

Open a command-line tool and run the following command into the same folder you find the `docker-compose.yaml` file.

* To install all needed containers run:`docker-compose up -d`. 
  
    _It brings up also the **PostgreSQL** database and the **Adminer**, a web tool to allow you manage databases._

 Note: After all automatic downloads and installations, please wait 10-15 seconds until everything settles up. Then navigate to http://localhost:8167/swagger-ui.html in your favorite browser and enjoy! The initial password of the `admin` user is `123456`.
  
 Note: Adminer will be available in  http://localhost:8168 The default user is `postgres` and its password is `postgres`


4. #### How to Stop, Start, and Remove

* To stop them all run: `docker-compose stop`

  
* To restart them all run: `docker-compose start`
  

* To uninstall by removing the containers run: `docker-compose down`


Thanks a lot and keep working!

_Julio Vinicius_
