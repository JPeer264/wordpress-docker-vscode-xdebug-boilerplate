# Wordpress Docker xDebug Boilerplate

This boilerplate is to debug Wordpress websites using Docker and VSCode

## Usage

> Make sure Docker is running and the [PHP Debug](https://marketplace.visualstudio.com/items?itemName=felixfbecker.php-debug) extension for VSCode is installed


1. Run the docker instance
```sh
$ docker-compose up
```

2. Open http://localhost:8000

3. Open the debugger tab on the sidebar and run `Listen for XDebug`

4. Set anywhere in your PHP files a breakpoint
