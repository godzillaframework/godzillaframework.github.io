## Welcome To Godzilla Framwork Website

## Installation:
```
go get -u github.com/godzillaframework/godzilla
```

## Supported Platforms:
- macOS
- Linux
- Windows

## Features:
- Fast
- Lightweight
- Secure
- Easy Peasy :)

## Examples

- basic api
```
func main() {
	gz := godzilla.New()

	gz.Get("/index", func(ctx godzilla.Context) {
		ctx.SendString("Hello EveryOne!!!")
	})

	gz.Start(":9090")
}
```
