
To get up and running with this repo   

```
To test how to run a repo without go.mod
Remove the go.mod file from this repo and run this command...
go mod init github.com/stormasm/yhoo-gq1

Otherwise since go.mod is present...
go get -t
go run quote/main.go ui

Or to install a binary

cd quote
go install

quote will now be installed in $HOME/go/bin

Then once quote is installed go to any directory and type

quote ibm
quote aapl
quote msft
```

A continuation of code removal starting in this order

Original Code
https://github.com/stormasm/go-quote

Partial Removal
https://github.com/stormasm/markcheno-gq

Even more code got whacked
https://github.com/stormasm/yhoo-gq1
