<p align="center">
<a href="http://boxshop.mn/">
<img src="https://github.com/tortuvshin/boxshop/blob/master/public/img/logo.png"/>
</a><br>
	<b>Цахим худалдааны систем</b>
</p>


Энэхүү онлайн худалдааны системийг Laravel 5.4. хувилбар дээр хөгжүүлж байна.

## Сэрвэрийн үзүүлэлт

	PHP >= 5.6.4
	MySQL >= 5.7
	OpenSSL PHP Extension
	PDO PHP Extension
	Mbstring PHP Extension
	Tokenizer PHP Extension
	XML PHP Extension


<a name="installation"></a>
## Суулгах

Дараах коммандыг ажиллуулж энэхүү төслийг clone хийж авна:

```
git clone https://github.com/tortuvshin/ecommerce.git
```

Composer татаж суулгана

```
[Composer татах](https://getcomposer.org/download/)
```

Дараа нь, энэхүү төслийг татаж авсан хавтаст орж composer update/install комманд ажиллуулна

```
composer install
```

Nodejs татаж суулгана 

```
https://nodejs.org/en/download/
```

NPM сангууд татах
```
npm install
```

Хэрвээ Window үйлдлийн систем  болон VM ашиглаж хөгжүүлэлт хийж байгаа бол дараах коммандыг ажиллуулна: 
```
npm install --no-bin-links
```

Laravel Mix ашиглах

```
npm run dev
```

## Тохируулах

Дараа нь .env-example файлыг өөрчилж .env болгон өөрийн өгөгдлийн сан болон серверийг тохируулна

Өгөгдлийн санг үүсгэж тохируулсаны дараа дараах коммандаар хүснэгтүүдийг үүсгэнэ:

```
php artisan migrate
```

Туршилтын өгөгдөл дараах коммандаар оруулна:

```
php artisan db:seed
```
	
```
php artisan key:generate
```

reChaptcha код авах: 

```
https://www.google.com/recaptcha/admin#list
```

```
RECAPTCHA_PUBLIC_KEY, and RECAPTCHA_PRIVATE_KEY
```

reCaptcha кодуудаа .env файлд оруулна. Жишээ нь: 

```
RECAPTCHA_PUBLIC_KEY = RecaptchaPublicKeyObtained

RECAPTCHA_PRIVATE_KEY = RecaptchaPrivateKeyObtained
```

***Тайлбар:*** ```APP_DEBUG == true``` буюу debug асаалттай байгаа үед reCaptcha хэрэглэхгүй


Туршилтын хэрэглэгчийн мэдээлэл

	Хэрэглэгчийн нэр: admin@admin.com
	Нууц үг: admin


[NODEJS]: https://nodejs.org/en/download/
[COMPOSER]: https://getcomposer.org/download/
[RECAPTCHA]: https://www.google.com/recaptcha/admin#list
