This repository contains generated golang code for:
* Event Family: https://desp.kroger.com/event-family/80e90c8b-366d-43f3-9fca-2b0240aebc26
* Version: v0.2.0

To use this in your go client, add the following requirements to your go.mod file.

```
module github.com/krogertechnology/my-go-client-application

go 1.13

require (
	github.com/actgardner/gogen-avro/v9 v9.0.0 // indirect
	github.com/rhammonds1-kr/desp-catalog-go-test-vents-testevents v0.2.0
	...
```