Blockchain in GO.

To test:

go run main.go
curl http://localhost:8080/
curl -X POST -d @data.json http://localhost:8080/

Requires an .env file set with the PORT you wish to use. By default its 8080.
