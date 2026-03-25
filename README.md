# Haxball İçin V6 Real Soccer Hazırlık Botu

Haxball için tarafımca geliştirilmiş v6 Real Soccer mapine entegre bir scripttir

## Özellikler

- Çift Mod Desteği: Tek bir değişkenle Lig veya Hazırlık modu arasında geçiş yapabilme.
- Esnek Harita Yapısı: Power (Standart) ve Yaylı mod desteği.
- Güvenlik Sistemi: Kaptan ve Admin giriş kodları ile yetkisiz erişimi engelleme.
- Webhook Entegrasyonu: Kayıt (REC), sohbet logları, ban kayıtları ve giriş-çıkış bilgileri için tam Discord webhook desteği.
- Özelleştirilebilir Oyun Fiziği: Power ve oyuncu teleport/disc ayarları.

## Kurulum ve Yapılandırma

Kod içerisindeki temel değişkenleri kendi ihtiyacınıza göre düzenleyerek botu yayına alabilirsiniz.

## Ayarlar

### Lig & Test

- `lig = true` → Lig modu açık / kapalı
- `test = true` → Test modu açık / kapalı

### Oyun Modu

- `mapstatus = 1` → Power modu
- `mapstatus = 2` → Yaylı modu

### Yetkilendirme

- `admcode` → Admin şifresi
- `kaptancode` → Kaptan şifresi

### Oda Süreleri

- `hzodasısüre` → Hazırlık odası süresi
- `ligodasüre` → Lig odası süresi

### Power Ayarı

- `powerdegeri` → Power gücü  
  Önerilen: `1.6`

### Korner Sistemi

- `kornerdısarıatmadurumu = 1` → Işınlama (standart)
- `kornerdısarıatmadurumu = 2` → Disc (daha güvenli)

### Discord

- `discord` → Sunucu davet linki

### Oda Ayarları

- `roomName` → Oda adı  
  Harita isimlerini kendine göre düzenlemeyi unutma

### Webhooklar

- `rec` → Kayıt webhook
- `chatlog` → Chat log webhook
- `banlog` → Ban log webhook
- `gircık` → Giriş/çıkış webhook

#### Webhook Bağlantıları

Discord sunucunuzla senkronize etmek için aşağıdaki alanlara kendi webhook linklerinizi eklemeyi unutmayın:

- `rec` → Maç kayıtlarının gönderileceği kanal
- `chatlog` → Tüm sohbet geçmişi
- `banlog` → Uzaklaştırılan oyuncuların bilgisi
- `gircık` → Odaya katılan ve ayrılanların takibi

---

Bu script tarafımca geliştirilmiştir.

Not: Botun stabil çalışması için harita (map) isimlerinin kod içerisindeki isimlerle birebir eşleştiğinden emin olun.
