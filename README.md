#### Kullanılan import linki
https://www.postman.com/collections/0ec4a3253588fe8be469

## Çiçeksepeti'nde comment işleminde kullanılan API için;

#### *  https://www.postman.com/collections/0ec4a3253588fe8be469  POSTMAN collection'ında bulunan API için cityName parametresine göre dönen response'da,

#### * cityName değerlerinin kontrolü için entegrasyon testi yazılması,

#### Params
Key       Value

cityName ankara     =>      Ankara ili için yapılan yorumlar listesi

cityName istanbul   =>      İstanbul ili için yapılan yorumlar listesi

cityName van        =>      status is 404

cityName null       =>       status is 400


## cityName: ankara    "Ankara ili için yapılan yorumlar listesi"
![ankara](https://user-images.githubusercontent.com/65242155/147604859-13b9a102-d1b3-4eff-8483-8fa2367f7c09.png)

## cityName: istanbul   "İstanbul ili için yapılan yorumlar listesi"
![istanbul](https://user-images.githubusercontent.com/65242155/147604891-d5f19808-131d-4792-9a49-e07e698552c2.png)

## cityName: van   "Status is 404"
![van](https://user-images.githubusercontent.com/65242155/147604922-c4cf922a-8418-4709-944c-814d22a45273.png)
![van2](https://user-images.githubusercontent.com/65242155/147604928-937d5a17-e261-462d-9430-fad9d1f71ca2.png)

## cityName: null  "Status is 400"
![null400_2](https://user-images.githubusercontent.com/65242155/147604971-5f6b3a9d-dbb4-4472-940f-4027e0ef3d06.png)
![null400](https://user-images.githubusercontent.com/65242155/147604965-0040fb37-28ef-401a-8441-97b7a19ad987.png)
