### termbox-go
---
https://github.com/nsf/termbox-go

```go
err := termbox.Init()
if err != nil {
  panic(err)
}
defer termbox.Close()


type Attribute uint16
const (
  ColorDefault Attribute = iota
  ColorBlack
  ColorRed
  ColorGreen
  ColorYellow
  ColorBlue
  ColorMagenta
  ColorCyan
  ColorWhite
)


const (
  AttrBold Attribute = 1 << (iota + 9)
  AttrUnderline
  AttrReverse
)
```

```
```

```
```
