logging
=======


[Author](https://github.com/ngaut/log)

## How To Use


Get the code

```
go get -u github.com/EdenPP/log
```

Use the code


```go

import "github.com/EdenPP/log"

func main() {
	
	// Set log level, suport 
	log.SetLevelByString("INFO")
	log.SetOutputByName(conf.Log.GetLogPath() + conf.Log.GetLogFile())
	log.SetRotateByHour()
	log.SetHighlighting(false)

}

```