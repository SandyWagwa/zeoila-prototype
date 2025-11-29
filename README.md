# ZEOILA Cloud Prototype

This repository contains a prototype deployment of a cloud architecture using Docker and GitHub Actions.

## Steps
1. Clone repo
2. Build Docker image: `docker build -t zeoila-prototype .`
3. Run container: `docker run -d -p 5000:5000 zeoila-prototype`
4. Access app: `http://localhost:5000`
