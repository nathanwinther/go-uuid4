# Go programming language uuid4 package

Create Version 4 UUIDs as specified in RFC 4122

## Usage

    package main
    
    import (
        "fmt"
        "github.com/nathanwinther/go-uuid4"
    )
    
    func main() {
        u, err := uuid4.New()
        if err != nil {
            panic(err)
        }
        fmt.Println(u)
    }

