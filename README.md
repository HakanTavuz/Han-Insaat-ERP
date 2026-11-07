<div align="center">

<img src="logo.png" alt="Han İnşaat" width="320">

# Han Sipariş

**Yapı malzemesi firması için masaüstü sipariş ve cari takip programı (ERP)**

Excel'le yürütülen sipariş sürecini tek bir uygulamada toplar — şu an bir firmada günlük kullanımda.

![Sürüm](https://img.shields.io/github/v/release/HakanTavuz/han-erp-surum?label=s%C3%BCr%C3%BCm&color=D0222B)
![Platform](https://img.shields.io/badge/platform-Windows-0078D6)
![Çalışma](https://img.shields.io/badge/çalışma-çevrimdışı-2e7d32)
![Lisans](https://img.shields.io/badge/lisans-özel-555)

</div>

---

## Ne işe yarıyor

Firma eskiden her siparişi elle Excel'e giriyor, fiyatları elle hesaplıyor, eski kayıtları dosya yığınından bulmaya çalışıyordu. Program bunların hepsini tek yerde topluyor:

|  |  |
|---|---|
| 🧾 **Sipariş oluşturma** | Müşteri ve ürün otomatik tamamlanıyor; tutar, KDV ve toplam kendiliğinden hesaplanıyor |
| 📄 **PDF & Excel çıktısı** | Antetli teklif ve formüllü tablo, tek tıkla |
| 💳 **Cari takip** | Müşteri bakiyesi, hesap ekstresi, çek/senet ve taksit yönetimi |
| 🏷️ **Fiyat listesi okuma** | Tedarikçi fiyat listesi PDF'ini okuyup ürün fiyatlarını toplu günceller |
| 💬 **WhatsApp** | Teklifi/siparişi müşteriye uygulama içinden gönderme |
| 📊 **Raporlar** | Dönemsel satış ve ciro raporları |

Tamamen **çevrimdışı** çalışır, veriler kullanıcının bilgisayarında kalır. Yeni sürümler **kendini otomatik günceller**.

## Nasıl yapıldı

- **Masaüstü uygulama** — Python + yerel web sunucusu; kendi penceresinde açılır, kurulum sihirbazıyla gelir
- **Veritabanı** — SQLite; her açılışta otomatik yedek
- **Çıktı** — PDF (ReportLab) ve formüllü Excel (openpyxl)
- **Dağıtım** — GitHub Actions ile derlenir, makine koduna çevrilir (Nuitka) ve kendini otomatik günceller

## Telif ve Kullanım

**© 2026 Hakan Efe Tavuz. Tüm hakları saklıdır.**

Bu yazılım özeldir (proprietary). Kaynak kodu ve derlenmiş sürümleri, yazarın yazılı izni olmadan **kopyalanamaz, çoğaltılamaz, dağıtılamaz, değiştirilemez, ters mühendislikle çözülemez** ve ticari ya da ticari olmayan hiçbir amaçla kullanılamaz.

Bu depo yalnızca tanıtım amacıyla herkese açıktır; yazılımın kendisi için herhangi bir kullanım hakkı vermez. İzin ve iş birliği için: [LinkedIn](https://www.linkedin.com/in/hakanefetavuz)
