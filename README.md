# WebServer with Go

A simple web server implemented in Go, serving static files and handling basic HTTP requests.

## Directory Structure

```
WebServer-with-Go/
|-- static/
|   |-- index.html
|   |-- form.html
|-- README.md
|-- main.go
|-- go.mod
```

## Description

This repository contains a basic implementation of a web server using the Go programming language. The server serves static HTML files located in the `static/` directory and handles basic HTTP requests.

## Features

1. Serving Static Files: The web server serves static HTML files such as `index.html` and `form.html` from the `static/` directory.

2. Hello Handler: Accessing the path `/hello` with a GET request returns a "Hello there" message.

3. Form Handler: Accessing the path `/form` with a POST request displays a "POST Request Successful" message and prints form data (name and address) submitted by the client.

## Getting Started

1. Clone this repository to your local machine:

   ```sh
   git clone https://github.com/your-username/WebServer-with-Go.git
   ```

2. Navigate to the project directory:

   ```sh
   cd WebServer-with-Go
   ```

3. Build and run the server:

   ```sh
   go run main.go
   ```

4. Open your web browser and visit [http://localhost:8080](http://localhost:8080) to access the web server. You can also try accessing [http://localhost:8080/hello](http://localhost:8080/hello) and [http://localhost:8080/form](http://localhost:8080/form) to see the different handlers in action.

## Usage

This web server is a basic example of serving static files and handling HTTP requests using Go. You can use this project as a starting point to build more complex web applications or APIs.

Feel free to modify or expand upon the code to include additional features, improve error handling, or integrate with other parts of your application.

## Contributing

Contributions are welcome! If you have any improvements or additional features you'd like to add, please feel free to fork this repository and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).