Sample project demonstrating how to integrate Sidekiq and Redis into an existing Rails project, as described in [How To Add Sidekiq and Redis to a Ruby on Rails Application](https://www.digitalocean.com/community/tutorials/how-to-add-sidekiq-and-redis-to-a-ruby-on-rails-application)
chmod +x init.sql
chmod +x entrypoints/docker-entrypoint.sh
chmod +x entrypoints/sidekiq-entrypoint.sh
docker-compose up -d
docker-compose logs
docker-compose ps
#env
DATABASE_NAME=
DATABASE_USER=
DATABASE_PASSWORD=
DATABASE_HOST=
REDIS_HOST=
