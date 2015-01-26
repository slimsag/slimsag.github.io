{
    "title": "Why 'slimsag'?",
    "sidebar": true,
    "weight": "2"
}

I know you've probably thought it at least once.

It's not intended to be off-putting or harmful (oops?), rather, it's a description of my public appearance in the eye's of others.

- People say I am rather slim (at nearly 6ft tall and 1.5ft wide), but _I feel normal_.
- My name is _Stephen Alexander Gutekanst_ (S.A.G.), but _I call myself just 'me'_.

## _"But! ... I'm still confused!"_

Example code to get you started, then, perhaps?

```
package life

import "runtime"

type SAG struct {
	Name string
	HeightFt, WidthFt float64
}

func (SAG) code(lang string) {
	if lang != "Go" {
		panic("I think an exception has occured?")
	}
	for{
		runtime.Gosched()
	}
}

func main() {
	var slimsag = &SAG{
		Name: "Stephen Alexander Gutekanst",
		HeightFt: 5.9,
		WidthFt: 1.7,
	}
	go slimsag.code("Go")
}

```
