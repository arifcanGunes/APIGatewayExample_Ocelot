# apigatewayexample_ocelot

Bu proje, .NET 8 ve [Ocelot](https://ocelot.readthedocs.io/en/latest/) kullanarak basit bir API Gateway örneği sunar.  
Gateway ile birlikte üç örnek mikroservis (API1, API2, API3) içerir.

---

## Özellikler

- .NET 8 desteği
- Ocelot tabanlı API Gateway
- Üç örnek backend API
- Temel Ocelot konfigürasyon dosyaları
- Lokal geliştirme ve test için hazır yapı

---

## Kurulum ve Çalıştırma

1. NuGet paketlerini yükleyin:
    ```sh
    dotnet restore
    ```
2. API1, API2 ve API3 projelerini başlatın.
3. Ardından API_Gateway projesini başlatın.
4. Tüm API'lere gateway üzerinden erişebilirsiniz.

---

## Proje Yapısı

```
API_Gateway_Ocelot/
│
├── API_Gateway/      # Ocelot API Gateway projesi
├── API1/             # Örnek mikroservis 1
├── API2/             # Örnek mikroservis 2
├── API3/             # Örnek mikroservis 3
└── ...
```

---

## Kaynaklar

- [Ocelot Belgeleri](https://ocelot.readthedocs.io/en/latest/)
- [.NET 8 Belgeleri](https://learn.microsoft.com/en-us/dotnet/core/whats-new/dotnet-8)

---

Herhangi bir katkı veya öneri için pull request gönderebilirsiniz.
