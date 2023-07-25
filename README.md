# Laravel-breeze study
### laravel과 breeze로 react typescript 생성 및 구동 테스트

### - 기본 설치
- composer는 기본적으로 설치[(설치하기)](https://getcomposer.org/doc/00-intro.md)
```shell
composer create-project laravel/laravel breeze
cd breeze
```
- breeze install
```shell
composer require laravel/breeze --dev
```
- 더 많은 breeze 설치 option은 [여기서](https://laravel.com/docs/10.x/starter-kits)
- 리엑트 타입스크립트를 설치
 ```shell
php artisan breeze:install react --typescript
```
- 설치 완료 후 `npm run dev`를 하면 vite engine이 올라옴
- nginx.conf의 내용을 nginx에 적용해서 구동하면 완료
