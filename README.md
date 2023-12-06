
Follow https://github.com/mattermost/openops for basic instructions.

For seeing running containers:  docker compose ps

For stopping containers: docker compose down

For starting containers: docker compose -f docker-compose.yml -f docker-compose.local.yml up (-d optional)

For init from scratch: env backend=localai ./init.sh
 
