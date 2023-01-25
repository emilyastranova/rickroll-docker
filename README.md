# Rickroll-Docker

This project is a simple demonstration of how to create a Docker container that hosts a web server that redirects incoming requests to the [Never Gonna Give You Up](https://www.youtube.com/watch?v=dQw4w9WgXcQ) music video on YouTube.

## Prerequisites

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/) (if using `docker-compose.yml`)

## Usage

1. Clone the repository

2. ```bash
   git clone https://github.com/tyleraharrison/rickroll-docker.git
   ```

3. ```bash
   cd rickroll-docker
   docker-compose up -d
   ```

4. Access the redirect by opening `http://localhost` in your web browser

## Note

This is a demo project just to illustrate how to create a Docker container that redirects incoming requests to a specific website. Please use a more specific redirect rule in a production environment.

Enjoy the music!

## TODO

- [ ] Add meta tags with images/alternative title
