# Yazılım Kurulumu, Yönetimi ve Denetim Süreçleri

Sistem yönetimi ve yazılım yaşam döngüsü denetimi üzerine teknik bir inceleme.

**Hazırlayan:** Hazal Çorbacı  
**Bölüm:** Bilgisayar Programcılığı 1. Sınıf

---

## 📝 Sunum Özeti
Yazılım kurulumu; bir yazılımın bilgisayar sistemine tanıtılması, yapılandırılması ve çalışmaya hazır hale getirilmesi sürecidir. Bu sürecin doğru yönetilmesi, sistem kararlılığını korumak ve güvenlik açıklarını en aza indirmek için kritiktir.

## ⚙️ Teknik Detaylar

### 1. Kurulum Yöntemleri
* **Manuel Kurulum:** Kullanıcı onayıyla ilerleyen standart yöntem.
* **Sessiz (Silent) Kurulum:** Parametreler kullanılarak arayüzsüz yapılan otomatik işlem.
* **Ağ Üzerinden Dağıtım:** Tek merkezden (MSI, SCCM) binlerce bilgisayara gönderim.
* **Portatif (Portable):** Kurulum gerektirmeyen, doğrudan çalışan yapılar.

### 2. Kurulum Öncesi Hazırlık
* **Donanım Uyumluluğu:** CPU, RAM ve disk alanı kontrolleri.
* **Yazılım Bağımlılıkları:** Java, .NET ve Python gibi kütüphanelerin kontrolü.
* **Yedekleme:** Mevcut sistem verilerinin korunması.

### 3. Sistem Entegrasyonu ve Kayıt
* **Kayıt Defteri (Registry):** Yazılım parametrelerinin işletim sistemine kaydedilmesi.
* **Ortam Değişkenleri:** PATH tanımlamaları ile sistem genelinde erişim sağlama.

### 4. Lisans Modelleri
* **Açık Kaynak:** Özgürce değiştirilebilen lisanslar (MIT, GNU).
* **Ticari Yazılımlar:** Ücretli ve kullanım kısıtlamalı yapılar.
* **SaaS:** Bulut tabanlı, abonelik usulü kullanım.

## 🛡️ Güvenlik ve Denetim
* **Hash Doğrulama:** Dosya orijinalliği için SHA-256 kontrolü.
* **Dijital İmza:** Yayıncı kimliğinin doğrulanması.
* **Sandbox:** Şüpheli yazılımların izole ortamda test edilmesi.
* **Versiyonlama:** Yazılımın sürüm takibi (Semantic Versioning - v2.1.0).

## 🧹 Yazılım Kaldırma
* **Artık Dosyalar:** %AppData% ve Temp klasörlerindeki verilerin temizliği.
* **Kayıt Defteri Temizliği:** Geçersiz anahtarların silinmesi.

---
> **Sonuç:** Doğru kurulum ve sıkı denetim,
