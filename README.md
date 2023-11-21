# docker_flask_homework
This assignment aims to provide hands-on experience in Dockerizing Flask applications, first individually and then using Docker Compose for managing multiple applications.

Setting Up and Dockerizing a Flask App:
1. Create app.py, dockerfile and requirements.txt
2. Created a simple addition flask app on google shell
3. Built my docker container using docker build -t shaikh .
4. Ran my app via docker docker run -p 8005:5000 shaikh on port 8005
5. Used docker stop <container_id> to stop running and docker PS to show which container is running
