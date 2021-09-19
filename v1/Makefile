build1:
	protoc  --go_out=. --go_opt=paths=source_relative --go-grpc_out=. --go-grpc_opt=paths=source_relative **/*.proto
build2:
	protoc  --go_out=. --go_opt=paths=import --go-grpc_out=.  **/*.proto
build3:
	protoc  --go_out=. --go_opt=paths=import --go-grpc_out=.  **/*.proto
build4:
	protoc  --go_out=go --go-grpc_out=.  **/*.proto
build5:
	protoc  --grpc-gateway_opt generate_unbound_methods=true --go_out=go --go-grpc_out=.  **/*.proto
