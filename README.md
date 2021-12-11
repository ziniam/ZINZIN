
package main

import (
	"me"
)

type Bio map[string]string

func main() {
	for z,v  := range GetBio() {
		me.Printf("%+v: %+v\n", z, v)
	}
}

func GetBio() Bio {
	return Bio{
		"- 🌱 I’m currently learning":        "Front End | OOP | ",
    		"- 🤔 I'm looking for help":          "Anything😅",
		"- 💬 Ask me about":                  "Python, JavaScript, C++",
		"- 📫 How to reach me:":              "https://github.com/ZinV14#you-can-connect-with-me",
	}
}
