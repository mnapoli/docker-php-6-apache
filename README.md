# Php 6 + Apache docker image
> PHP6 is dead, long live PHP6!

## Usage
Assuming you are in your sources folder, just run
```
docker run -v $PWD:/var/www/html -p 8080:80 vdechenaux/php-6-apache
```
Now, you can play with PHP6 here: `http://localhost:8080/`
