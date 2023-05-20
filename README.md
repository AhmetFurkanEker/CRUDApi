# CRUDApi

# Product API

Bu proje, ürün işlemlerini gerçekleştirmek için bir API sağlar. CRUD (create, read, update, delete) işlevlerini içerir ve verileri bir veritabanında depolar.

## Özellikler

- Tüm ürünleri listeleme
- Belirli bir ürünün ayrıntılarını getirme
- Yeni bir ürün oluşturma
- Bir ürünü güncelleme
- Bir ürünü silme

## Başlangıç

Bu API'yi çalıştırmak için aşağıdaki adımları izleyin:

1. Proje dosyalarını bir dizine indirin veya kopyalayın.
2. `appsettings.json` dosyasını açın ve veritabanı bağlantı dizesini güncelleyin.
3. Proje dosyalarını bir ASP.NET Core uygulaması olarak derleyin.
4. Uygulamayı başlatın ve API'ye istekler yapmaya başlayın.

## API Endpoints

- `GET /api/product`: Tüm ürünleri listeler.
- `GET /api/product/{id}`: Belirli bir ürünün ayrıntılarını getirir.
- `POST /api/product`: Yeni bir ürün oluşturur.
- `PUT /api/product/{id}`: Bir ürünü günceller.
- `DELETE /api/product/{id}`: Bir ürünü siler.
