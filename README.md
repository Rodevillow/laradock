<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

## <center>Installation for development</center>

Best way for start this app is Docker via Laravel [Sail](https://laravel.com/docs/8.x/sail#installing-sail-into-existing-applications)

-   You have to [install Docker](https://docs.docker.com/engine/install/) for your OS.
-   Start Docker app on your computer.
-   Use [Sail](https://laravel.com/docs/8.x/sail#installing-sail-into-existing-applications) (to run Docker container) write command:

```
sail up
```

## <center>Default url for development</center>

<br>

After successfuly instalation, you can get access to server by this url --> [http://localhost:80](http://localhost:80)

<br>

## <center>Mysql access</center>

<br>

To get access to MySql container you can connect to mysql container CLI and write command:

```
mysql -h 127.0.0.1 -P 3306 -u sail -p
```

### Mysql pass: <strong>password</strong> (from your .env)

```
use laravel
```

<br>

#### [Laravel documentation](https://laravel.com/docs).
