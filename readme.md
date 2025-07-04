# 📡 VPN Trafiği Sınıflandırma Projesi

Bu çalışma, şifrelenmiş ağ trafiğinin VPN olup olmadığını, VPN ise hangi protokolü kullandığını ve bu trafiğin hangi uygulama türüne ait olduğunu anlamaya yönelik bir makine öğrenmesi uygulamasıdır. Projede USBVPN2022 veri seti kullanılmış ve analizler Python diliyle, Google Colab ortamında gerçekleştirilmiştir.

## 🎯 Proje Amacı
- Şifreli trafiğin VPN taşıyıp taşımadığını tespit etmek
- VPN trafiğinin hangi protokole (OpenVPN, SSTP, L2TP/IPSec vb.) ait olduğunu belirlemek
- VPN trafiğinin taşıdığı uygulama türünü (streaming, meet, mail, ssh, non_streaming) tahmin etmek

## 📊 Kullanılan Yöntemler
- Veri analizi ve görselleştirme (matplotlib, seaborn, pandas)
- RandomForest sınıflandırma modeli
- Özellik önemi analizi
- Dengesiz veriyle başa çıkmak için örnekleme

## 🔍 Öne Çıkan Grafikler
- VPN ve Non-VPN trafiğinin boyutsal dağılımı
- Uygulama türlerine göre akış sayısı ve byte büyüklükleri
- VPN protokollerine göre TCP/UDP tercihleri ve ACK bayrağı kullanımı
- Confusion matrix, doğruluk ve F1 skoru gibi model performans ölçümleri

## 🧠 Notlar
- Veri seti: [USBVPN2022 - Zenodo](https://zenodo.org/record/7301756)
- Grafikler hem tüm veri setiyle hem de dengelenmiş örneklerle oluşturulmuştur
- Proje akademik amaçlıdır, veri anonimleştirilmiştir

## 🧑‍💻 Geliştiren
**Umut Kocaoğlu – 201118058**  
Danışman: Dr. Öğr. Üyesi Özgür Tonkal  
Haziran 2025

---

