# docker_flask_homework
This assignment aims to provide hands-on experience in Dockerizing Flask applications, first individually and then using Docker Compose for managing multiple applications.

Setting Up and Dockerizing a Flask App:
1. In folder Part1 contains app.py, dockerfile and requirements.txt
2. Created a simple addition flask app on google shell
3. Built my docker container using docker build -t shaikh .
4. Ran my app via docker docker run -p 8005:5000 shaikh on port 8005
5. Used docker stop <container_id> to stop running and docker PS to show which container is running


Part Two: Multi-Container Setup with Docker Compose:
1. Created two flask apps each in their own folder with the requirements.txt and dockerfile
2. Made sure both apps are working and have unique functionality to each other
3. Created a docker compose file which routes the path to each flask
4. On terminal of folder with the compose file I entered docker-compose up --build which built and ran both apps at the same time on different ports via 5001 and 5002, local port = 5000
5. Then used docker-compose up -d to run them in the background
