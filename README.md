# docker-php-mysql-nginx

## Usage

Launch Terminal or CMD, CD into a directory where you usually keep your codes.

For the first time, clone this repository by using the command below:

```
git clone https://github.com/maxsquared/docker-php-mysql-nginx.git
```

Then anytime you need to run php just run the following command

```
cd docker-php-mysql-nginx
docker-compose up
```

Wait for magic to happen

Make any chances in **src** directory then you are good to go.

Use port **8080** for the website: _http://localhost:8080_

### MySQL

Username: root

Password: **supersafepassword**

Password can be change in _docker-compose.yml_

When connecting to MySQL server ensure to use server name: **php_mysql_1**, localhost will not work.
