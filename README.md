# Docker - Nginx

Bu uygulama, Patika'nın düzenlediği AloTech Fullstack Bootcamp'i bitirme projesinin bir parçasıdır.

#### Grup - 5
> Eren Tanrıverdioğlu - Furkan Aktaş - Parahat Nepesov - Timur Turbil

## Uygulamanın İşlevi

Proje kapsamında geliştirilen uygulama ve servislerin, MySQL ve Nginx servisinin Docker aracılığıyla deploy edilebilmesi için hazırlanmış repositorydir.

Tüm servisler çalışıp birbirleriyle iletişim kurabiliyor.

Subdomainler arasında cookie paylaşımı yapılamadı.

## Kurulum

* Projeyi klonlayın:
`git clone https://github.com/Alotech-Bootcamp-5-Grup/docker-nginx-test.git`

- Uygulama klasörüne girin:
`cd docker-nginx-test`

- docker-compose.yaml dosyasını düzenleyin.

- Servis ve uygulamaların .env dosyalarını düzenleyin.

- nginx'in default.conf dosyasını düzenleyin.

- Projeyi çalıştırın:
`docker-compose up --build`
