{
    "title": "Why 'slimsag'?",
    "sidebar": true,
    "weight": "2"
}

I know you've probably thought it at least once.

It's not intended to be off-putting or harmful -- but rather a representation of my public self, in the eye's of others.

- People say I am rather slim (at nearly 6ft tall and 1.5ft wide), and yet _I feel normal_.
- I'm called _Stephen Alexander Gutekanst_ (S.A.G.), but _I still call myself just 'me'_.

## _"I'm still confused!"_

Some example code to get you started, then:

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
		WidthFt: 1.4,
	}
	go slimsag.code("Go")
}
```
