logging
=======


[Author](https://github.com/ngaut/log)

## How To Use


Get the go code

```
go get -u github.com/EdenPP/log
```

Use the package


```go

import "github.com/EdenPP/log"

func main() {


    filePath := "/var/log/test.log"
	
	// Set log level, suport 
	log.SetLevelByString("INFO")
	
	// set file path
	log.SetOutputByName(filePath)
	
	// rotate by houre
	log.SetRotateByHour()

}

```