Not much on this repo, just testing how to setup and write a GO package

## installation
```bash
go get github.com/GoodnessEzeokafor/arithmetic
```

## usage
```go
package main

import (
	"fmt"
	"github.com/GoodnessEzeokafor/arithmetic"
)
func main(){
	addition := arithmetic.Add(1,2)
	fmt.Println(addition)
}
```
