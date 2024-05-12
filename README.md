# CI-CD for Sport Group

### !!! Work in progress !!!

## Backend deployment
1. Install [Docker](https://docs.docker.com/get-docker/), [Docker Compose](https://docs.docker.com/compose/install/), [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
2. Clone the repository
3. [Login](https://docs.github.com/en/packages/working-with-a-github-packages-registry/working-with-the-container-registry) to docker for GitHub packages
4. Create database for Auth service # TODO add instructions
5. Run migrations
6. Run `docker-compose up -d` to start the services
7. Profit!