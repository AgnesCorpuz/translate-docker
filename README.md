1. Build the Docker Image by running the command in your terminal: `sudo docker build -t cavcorpuz/translate-docker .`
2. Run the Docker container using: `sudo docker run --name translate-docker -p 443:443 -d cavcorpuz/translate-docker`
3. Open your web browser and navigate to `https://localhost:443/?conversationid={{conversationid}}&language={{language}}`
4. Stop the container by typing `Ctrl + C` in your terminal or stop and remove containers using: `docker-compose down`.