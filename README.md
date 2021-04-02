## 10Athletes Dockerized

## Usage

```shell
$ git clone https://github.com/samsrose/congenial-system.git && cd congenial-system

# Setup
$ docker-compose run frontend yarn
$ docker-compose run backend bin/rails db:create db:migrate

# Start
$ docker-compose up -d

# Open frontend
$ open http://localhost:3000 # You'll see React page
$ open http://localhost:3001 # You'll see Rails page

# Check backend API

### Backend

Rails6, Ruby3, PostgreSQL, DockerCompose, Docker

### Frontend

React16, Babel, Jest, ESLint