We have to install golang-migrate
https://github.com/golang-migrate/migrate/tree/master/cmd/migrate

Create and update .env file following .env.example

Let create the migartion file by command:

`migrate create -ext=sql -dir=internal/database/migrations -seq {migration_name}`

`make migrate_up` to run the migrations

`make migrate_down` to revert the migrations

