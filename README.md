
# MultiPHP Docker


MultiPHP Docker is an empty docker project where you can run multiple PHP versions (containers) simultaneously.

PHP versions supported: 5.3, 5.6, 7.4 & 8.1

Each PHP version is assigned its own port number (see below).

URL | PHP version | Folder
----| ------------| --------
http://localhost:8853 | 5.3 | `html/php53`
http://localhost:8856 | 5.6 | `html/php56`
http://localhost:8874 | 7.4 | `html/php74`
http://localhost:8881 | 8.1 | `html/php81`


Save your PHP project files in prepared folders in the `html` folder. 


## Installation

Firstly, download, install and launch Docker Desktop.

Then clone/download the repo.

Finally, enter the phpdocker folder via your command-line/Terminal and run the command:

```bash
docker-compose up -d
```

To shutdown all containers, run:
```bash
docker-compose down -v
```
