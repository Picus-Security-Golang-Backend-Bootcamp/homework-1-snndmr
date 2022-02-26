# Go Library App
![Golang](https://img.shields.io/badge/go-1.17-green) ![AskMe](https://img.shields.io/badge/Ask%20me-anyting-orange) ![FollowMe](https://img.shields.io/github/followers/snndmr?style=social)

A library application with search and listing features written in Go language.

### Project Structure

```properties
├── helper
│   └── cli.go
├── models
│   └── book.go
├── output
│   └── output.png
├── utils
│   ├── common.go
│   └── storage.go
└── main.go
```

### Usage
+ To list all books.
	
	```cmd
	go run main.go list
	```

+ To search within books by book name. You don't need to type the exact title of the book to search.
	
	```cmd
	go run main.go search book_title
	```
	
	```cmd
	go run main.go search boo
	```

+ Sample scenario of the application.

	![ExampleRun](output/output.png)
