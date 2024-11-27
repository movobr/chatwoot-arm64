Welcome to chatwoot-arm64 repo

On your first run, please keep in mind that database prepare is required.
To do that, on your first docker-compose up -d, run the command:

docker exec chatwoot-app bundle exec rails db:chatwoot_prepare
