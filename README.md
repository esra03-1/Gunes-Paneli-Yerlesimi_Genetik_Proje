# Genetik Algoritma ile Güneş Paneli Optimizasyonu (Senaryo 1)

Bu proje, BLG-307 Yapay Zeka Sistemleri dersi kapsamında geliştirilmiştir.

## 📌 Proje Tanımı
Öğrenci numaramın son hanesi (1) gereği **Senaryo 1: Güneş Paneli Yerleşiminde Optimum Eğim ve Yön** konusu seçilmiştir.
Amaç, güneş panellerinden alınan toplam enerji verimini maksimize eden optimum eğim (x1) ve yön (x2) açılarını Genetik Algoritma kullanarak bulmaktır.

## ⚙️ Matematiksel Model
* **Amaç Fonksiyonu:** `y = 6x₁ + 4x₂ - 0.1x₁²`
* **Değişkenler:**
    * x1 (Eğim): [10, 45] derece arası
    * x2 (Yön): [0, 90] derece arası
* **Kısıtlar:**
    * Fiziksel Kısıt: `x₁ + 0.5x₂ ≤ 60`
    * Minimum Yönlenme: `x₂ ≥ 15`

## 🚀 Kurulum ve Çalıştırma
Proje Python dili ile yazılmıştır ve Google Colab üzerinde sorunsuz çalışmaktadır.

1. `.ipynb` uzantılı dosyayı indirin.
2. Google Colab veya Jupyter Notebook ile açın.
3. Tüm hücreleri çalıştırın.

## 📋 Kullanılan Kütüphaneler
* `numpy`: Vektörel işlemler ve popülasyon yönetimi için.
* `matplotlib`: Uygunluk (fitness) grafiğini çizdirmek için.
* `random`: Rastgele sayı üretimi için.

## 👤 Öğrenci Bilgileri
* **Ad Soyad:** Esra Gögebakan
* **Okul No:** 2212721001
