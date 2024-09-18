<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

# Dental

## Technologies

<p align="center">
  <a href="https://github.com/Muhammadislom">
    <img src="https://skillicons.dev/icons?i=docker,nginx,laravel,postgresql" />
  </a>
</p>

### Docker Run
#### Docker up containers
```
docker-compose up -d
```
#### composer install
```
docker exec -t php_fpm_dental_api composer install
```
#### Laravel key generate
```
docker exec -t php_fpm_dental_api php artisan key:generate
```
#### migration
```
docker exec -t php_fpm_dental_api php artisan migrate
```

### Postgres shell
```
docker exec -t postgres psql -d my -U my
```
