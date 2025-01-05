We have to install golang-migrate
https://github.com/golang-migrate/migrate/tree/master/cmd/migrate

Let create the migartion file by command:

migrate create -ext=sql -dir=internal/database/migrations -seq init
