# colorstring

colorstring is a [Go](http://www.golang.org) library for outputting colored
strings to a console using a simple inline syntax in your string to specify
the color to print as.

For example, the string `[blue]hello [red]world` would output the text
"hello world" in two colors. The API of colorstring allows for easily disabling
colors, adding aliases, etc.

## Installation

Standard `go get`:

```
$ go get github.com/mitchellh/colorstring
```

## Usage & Example

For usage and examples see the [Godoc](http://godoc.org/github.com/mitchellh/colorstring).

The `Decode` function has examples associated with it there.
