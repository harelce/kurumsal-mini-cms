# 🚀 Kurumsal Mini CMS + E-Ticaret Sistemi

## ✅ Özellikler

- MVC Yapısı
- Admin Paneli (Rol Bazlı)
- Ürün, Haber, Galeri, Slider Yönetimi
- Sepet & Sipariş Sistemi
- Kupon & İndirim
- PDF Fatura
- Mail & SMS Gönderimi
- API Entegrasyonu
- Raporlama Paneli
- SEO & Yedekleme
- Kullanıcı Yorumları & Üye Girişi
- Wishlist (Favoriler)

---

## ⚙️ Kurulum

1. **Veritabanı Oluştur:**
   - phpMyAdmin veya terminalde boş bir veritabanı oluşturun: `kurumsal_mini_cms`
   - `/sql/kurumsal_cms_tum.sql` dosyasını import edin.

2. **Dosyaları Yükle:**
   - Tüm dosyaları sunucunuzun `public_html` veya domain köküne yükleyin.
   - `/public/` klasörü, domain kökü olarak tanımlanmalı (veya virtual host ile yönlendirme).

3. **Config Ayarları:**
   - `/config/database.php` dosyasını kendi veritabanı bilgilerinize göre düzenleyin.

4. **Kütüphaneler:**
   - `tcpdf/` → https://github.com/tecnickcom/TCPDF/releases → `src/` içeriğini `tcpdf/` klasörüne koyun.
   - `phpmailer/` → Composer ile: `composer require phpmailer/phpmailer` veya manuel indirin.
   - `vendor/` → Composer kullandıysanız otomatik oluşur.

5. **.htaccess:**
   - `/public/.htaccess` dosyası SEF URL için gerekli. Sunucunuzda `mod_rewrite` açık olmalı.

---

## 🔐 Admin Girişi

- URL: `http://siteniz.com/public/admin.php`
- Kullanıcı: `admin`
- Şifre: `123456`

> ⚠️ İlk girişten sonra şifreyi değiştirin!

---

## 📁 Örnek Görseller

`/public/assets/uploads/` klasörüne aşağıdaki örnek dosyaları manuel olarak ekleyin:
- `slider1.jpg`
- `default-urun.jpg`
- `default-haber.jpg`
- `galeri1.jpg`

---
✨ Başarılar dileriz!
