# 🗂 Fiili Dolaşım Raporu İndirici

Bu proje, Borsa İstanbul'da işlem gören şirketlerin **fiili dolaşımdaki pay oranlarını içeren Excel raporunu** [VAP (Veri Analiz Platformu)](https://www.vap.org.tr/) üzerinden otomatik olarak indirir ve **HTML formatına dönüştürerek okunabilir hale getirir**.

---

## 🚀 Ne Yapar?

- 📅 **Her hafta Salı–Cuma günleri** çalışır ve bir önceki günün fiili dolaşım verisini indirir.
- 📉 **Pazartesi günleri**, **önceki Cuma günü** verisini alır.
- 📁 İndirilen `.xls` veya `.xlsx` dosyasını otomatik olarak temizler ve **HTML tabloya çevirir**.
- 🧼 HTML tabloda boş satır ve sütunlar kaldırılır, sayı biçimleri düzenlenir.
- ⛔ Hafta sonları çalışmaz.

---

## 🧠 Kullanım Senaryosu

Bu script ile:

- Günlük olarak fiili dolaşım verilerini arşivleyebilirsiniz.
- HTML formatı üzerinden tabloyu bir web arayüzünde veya veri görselleştirme sisteminde kolayca kullanabilirsiniz.

---

## 🔧 Kurulum

1. Gerekli Python kütüphanelerini kurun:

```bash
pip install selenium pandas openpyxl
```
