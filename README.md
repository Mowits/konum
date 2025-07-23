# Sistem Konumunu Gösteren C++ Programı

Bu program, Linux sistemde kullanıcı IP adresine göre konum bilgisini gösterir.  
`ip-api.com` servisi kullanılarak, program internet üzerinden JSON formatında konum bilgisi alır.

---

## Özellikler

- Kullanıcının IP adresine göre ülke, şehir gibi konum bilgisi alınır.
- `libcurl` kütüphanesi ile HTTP istekleri yapılır.
- Basit ve anlaşılır C++ kodu.

---

## Gereksinimler

- Linux işletim sistemi
- `g++` derleyici
- `libcurl` kütüphanesi

Ubuntu için kurulumu:


sudo apt-get update
sudo apt-get install g++ libcurl4-openssl-dev

### Derleme
g++ konum.cpp -o konum -lcurl

#### Çalıştırma
./konum
