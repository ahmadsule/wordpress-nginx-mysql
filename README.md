# wordpress-nginx-mysql
Use docker compose to create wordpress application including related webserver (nginx), mysql database and phpmyadmin

Prerequisite:
- docker is already installed and running
- docker compose plugin is already installed
- check docker version with command docker --version

  Step 1: Create project folder. For example /home/user/wordpress
  Step 2: Create subfolder nginx-conf.
  Step 3: Change directory to subfolder nginx-conf then create file nginx.conf
  Step 4: Move to project directory
  Step 5. Create file .env as environment variable
  Step 6: Create file docker-compose.yml
  Step 9. At command line, change directory to project directory.
  Step 10. Enter command: sudo docker compose up -d
  Step 11: Wait for execution until finish.
