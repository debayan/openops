
Follow https://github.com/mattermost/openops for basic instructions.

For seeing running containers:  docker compose -f docker-compose.yml -f docker-compose.local.yml ps

For stopping containers: docker compose -f docker-compose.yml -f docker-compose.local.yml down

For starting containers: docker compose -f docker-compose.yml -f docker-compose.local.yml up (-d optional)

For init from scratch: env backend=localai ./init.sh
 
