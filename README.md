<!-- <img src="https://raw.githubusercontent.com/t6tg/t6tg/master/img.webp" alt="capybara" />
 -->
```go
package main

import "fmt"

type aboutMe struct {
	pronouns    []string
	languages   []string
	hobbies     []string
	interesting []string
	frameworks  []string
	databases   []string
	etc         []string
}

func main() {
	t6tg := aboutMe{
		pronouns:    []string{"He", "Him", "They"},
		languages:   []string{"Go", "PHP", "Typescript", "Java"},
		hobbies:     []string{"Watch Anime", "Coding"},
		interesting: []string{"Rust", "Flutter"},
		frameworks:  []string{"Reactjs", "NextJS", "NestJS", "Gin", "Fiber", "Expressjs"},
		databases:   []string{"MongoDB", "MariaDB", "Postgresql", "SQL", "SQLite", "Redis", "Timescale TSDB", "Memcached"},
		etc:         []string{"Elasticsearch", "GraphQL", "nginx", "k8s", "docker"},
	}

	fmt.Printf("Pronouns: %v\n", t6tg.pronouns)
	fmt.Printf("Languages I Know: %v\n", t6tg.languages)
	fmt.Printf("My Hobbies: %v\n", t6tg.hobbies)
	fmt.Printf("Interesting in: %v\n", t6tg.interesting)
	fmt.Printf("Familiar Framework: %v\n", t6tg.frameworks)
	fmt.Printf("Database: %v\n", t6tg.databases)
	fmt.Printf("Etc: %v\n", t6tg.etc)
}
```
