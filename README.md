# Helper

这都是辅助函数，方便开发调用。

```bash
go get github.com/EasyMeta-App/helper
```

```go
package main

import "github.com/EasyMeta-App/helper"

func main() {
  resp := helper.RandString(5)
  fmt.Println(resp)
}
```

```
├── LICENSE
├── README.md
├── any2type.go
├── array.go
├── bot.go
├── config.go
├── crypto.go
├── gender.go
├── gender_test.go
├── go.mod
├── go.sum
├── html.go
├── init.go
├── json.go
├── names
│   ├── yob1880.txt
│   ├── yob1881.txt
│   ├── ...
├── numbers.go
├── random.go
├── strings.go
├── strings_test.go
└── validate.go

1 directories, 161 files
```
