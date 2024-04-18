# URL Shortener CLI Tool

The URL Shortener CLI Tool is a command-line interface (CLI) application that allows you to shorten URLs using the CleanURI API and store them in a PostgreSQL database. It provides commands to generate shortened URLs and list all previously shortened URLs.


### Command: shorten

Use the `shorten` command to shorten a URL.

```shell
node <name > <command > <url>
```

Replace `<url>` with the long URL that you want to shorten.

Example:

```shell
 app.js shorten https://www.example.com
 ```
 ### command: list

 Do same as for the shorten command.