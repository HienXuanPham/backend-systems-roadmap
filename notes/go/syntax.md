# Go syntax from my TCP Server project

`nil` means "nothing", no error
```go
err != nil
```
means: The error is not empty, so the program got error value.

`:=` means declare and initialize variables
```go
listener, err := net.Listen("tcp", addr)
```
