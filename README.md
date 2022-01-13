- 👋 Hi, I’m @dibyah
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
dibyah/dibyah is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

# docker commands

### build an image
    docker build --build-arg ALERT_GITHUB_PAT=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 --tag alert-api-service .

### run a container
    docker run -d -p 8000:5006 alert-api-service

### see running containers
    docker ps -a

### kill all containers
    docker rm $(docker ps -a -q)

### delete all images
    docker image prune -a -f
