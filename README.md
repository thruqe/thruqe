<img src="./Hand coding-bro.svg" width="160" alt="Hand coding illustration" />

**Hey, I'm Thruqe. I'm a student building software and contributing to open-source projects.**

```go
package main

import "fmt"

func main() {
	var s []rune
	for _, b := range []uint32{0x756854, 0x657172, 0x20, 0xE9, 0x20, 0x6D75, 0x20, 0x6F7270, 0x617267, 0x6F64616D, 0x72} {
		for v := b; v > 0; v >>= 8 {
			s = append(s, rune(v&0xFF))
		}
	}
	fmt.Println(string(s))
}
```

**I build critical microservices and end-user products.**

**I love web scraping & reverse engineering.**

_**If you are looking for someone to help you fix a problem or develop a solution that works, do not hesitate to contact me at [thruqe@gmail.com](mailto:thruqe@gmail.com)**_
