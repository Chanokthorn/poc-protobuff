build1:
	protoc  --go_out=. --go_opt=paths=source_relative --go-grpc_out=. --go-grpc_opt=paths=source_relative **/*.proto
build2:
	protoc  --go_out=go --go_opt=paths=import --go-grpc_out=go *.proto
