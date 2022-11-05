go mod init [project name] : Init go.mod is a package.json kind of
go get github.com/faiface/beep:      Download a dependency
go get github.com/gorilla/websocket: Download a dependency

main.go : Entrypoint of any Golang app


Define Types
A helpful pattern in Go is to define related struct types in one place. Let's create a types.go file in the types directory.

The song info will be in json format. First import that:

```golang
package types
import "encoding/json"
```