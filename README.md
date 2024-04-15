# Go-notes
my GO study notes
________________ 

go variables 

to declare variables 

```go

package main

import (
	"fmt"
)

func main() {
	MyVar := "hello world"
var Myvarr = "hello"
var myvar string="hello"
Myslice:=[]strin{"a","b"}
}

```
the scope is between two curly brackets of which we declare on it

to print 

```go

package main

import (
	"fmt"
)

func main() {
	MyVar := "hello world"
	fmt.Println(MyVar)
	fmt.Printf("%v fuck", MyVar)
}


```

__________________________

ended to page 12 of  Get Programming with Go


_________________________________________________________________________________


we have to way ro run code in golang 

at first with run command

```bash

go run main.go

```

at second with building source code

```bash

go build main.go
./main.exe

```

________________________________________

loops

```go

	for i := 0; i < 4; i++ {
		fmt.Println("yahya")
	}
	for {
		fmt.Println("yahyazzzz")
		break
	}
	for 5 == 6 {
		fmt.Println("yahyaxxx")
	}

```
____________________

switch statements

```go

	switch VaR:="hello";VaR {
	case "hello world", "zombe":
		fmt.Println(" is a hello word!")
		fallthrough
	default:
		fmt.Println(" is not a hello word!")
	}

```

____________________________________

if statemant

```go

	if 5 == 2 || 5%5 == 0 {
		fmt.Println("5 is not equal to 2")
	} else if 5 == 5 {
		fmt.Println("5 is equal to 2")
	}else{
		fmt.Printf("hello")
	}

```


______________________________________

end unit one in Get Programming with Go and to video 9 with fares walid

_________________________________________________-
