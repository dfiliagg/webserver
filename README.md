Sure, here is a suggested README file for your project:

```markdown
# WebServer

This project is a lightweight, custom-built web server written in C++. It supports HTTP requests, handles basic routing, and serves static files efficiently. Designed for simplicity and performance, it’s suitable for small applications, local development, or as an educational example of networking.

## Features

- Handles HTTP GET and POST requests
- Serves static files (HTML, CSS, JS, images)
- Basic routing capabilities
- Simple and efficient design

## Requirements

- C++17 or higher
- CMake 3.10 or higher

## Building the Project

1. Clone the repository:
    ```sh
    git clone https://github.com/dfiliagg/webserver.git
    cd webserver
    ```

2. Create a build directory and navigate into it:
    ```sh
    mkdir build
    cd build
    ```

3. Run CMake to generate the build files:
    ```sh
    cmake ..
    ```

4. Build the project:
    ```sh
    make
    ```

## Running the Server

After building the project, you can run the server using the following command from the `build` directory:

```sh
./webserver
```

By default, the server will start on port 8080. You can visit `http://localhost:8080` in your web browser to see it in action.

## Configuration

You can configure the server settings by modifying the `config.json` file located in the root of the project. This file allows you to set the port number and other server options.

## Directory Structure

- `src/` - Contains the source code for the web server.
- `include/` - Header files.
- `static/` - Directory for static files (HTML, CSS, JS).
- `config.json` - Configuration file for the server.

## Contributing

Contributions are welcome! Please fork the repository and open a pull request with your changes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Thanks to all the open-source projects and libraries that made this project possible.
```

You can adjust any sections as needed to better fit your project.
