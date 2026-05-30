# FC2 Video Bilgi Aracı 🎬

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Version](https://img.shields.io/badge/Version-1.0.0-green.svg)](https://twittervideodownloaderx.com/fc2_downloader_tu)
[![Status](https://img.shields.io/badge/Status-Active-brightgreen)](https://twittervideodownloaderx.com/fc2_downloader_tu)

> ⚠️ **Önemli Uyarı**: Bu proje yalnızca eğitim ve araştırma amaçları için tasarlanmıştır. Lütfen her zaman [FC2 Kullanım Koşulları](https://fc2.com/terms/) ve yargı bölgenizde geçerli olan telif hakkı yasalarına uyunuz.

---

## 📋 Proje Açıklaması

**FC2 Video Bilgi Aracı**, FC2 platformunda (FC2 Video, FC2 Blog ve gömülü içerikler dahil) **herkese açık** olarak erişilebilen video içeriklerinin meta verilerini analiz etmek ve sorgulamak amacıyla geliştirilmiş hafif bir web uygulamasıdır. Bu araç, kullanıcıların, araştırmacıların ve dijital arşivcilerin; video başlığı, açıklaması, yüklenme tarihi, dosya bilgileri, mevcut çözünürlükleri ve süre gibi teknik bilgilere, platform altyapısına müdahale etmeden veya güvenlik mekanizmalarını atlamadan erişmelerine yardımcı olur.

### ✨ Temel Özellikler

- 🔍 **URL Analizi**: Herkese açık FC2 video/blog bağlantılarını girerek ilgili meta verileri sorgama desteği
- 📊 **Meta Veri Gösterimi**: Başlık, açıklama, yayın tarihi, dosya bilgileri, mevcut çözünürlükler ve video süresinin net sunumu
- 🌐 **Türkçe Arayüz**: Türkiye ve dünya genelindeki Türkçe konuşan kullanıcılar için profesyonel, anlaşılır UI/UX tasarımıyla tam Türkçe dil desteği
- 📱 **Duyarlı Tasarım**: Masaüstü, tablet ve akıllı telefonlarda optimize edilmiş kullanıcı deneyimi
- ⚡ **Verimli İşleme**: İstemci tarafında doğrulama ve optimize edilmiş API iletişimi ile hızlı yanıt süreleri
- 🔒 **Gizlilik Öncelikli**: Kullanıcı verileri, sorgu geçmişi veya video içeriğinin hiçbir aşamada saklanmaması

---

## 🚀 Hızlı Başlangıç

### Çevrimiçi Kullanım (Önerilen)

Kurulum gerektirmeden doğrudan web arayüzümüze erişin:

👉 [https://twittervideodownloaderx.com/fc2_downloader_tu](https://twittervideodownloaderx.com/fc2_downloader_tu)

### Yerel Dağıtım (Geliştiriciler İçin)

```bash
# Depoyu klonlayın
git clone https://github.com/KullaniciAdiniz/fc2-video-info.git
cd fc2-video-info

# Bağımlılıkları yükleyin (Node.js sürümü örneği)
npm install

# Geliştirme sunucusunu başlatın
npm run dev
```

> 💡 Not: Yerel dağıtım yalnızca teknik araştırma ve öğrenme amaçları için önerilir. Üretim ortamında kullanım için resmi barındırılan hizmeti kullanmanızı tavsiye ederiz.

---

## 🛠️ Teknik Altyapı

| Bileşen | Kullanılan Teknoloji |
|--------|---------------------|
| Ön Yüz | HTML5 + CSS3 + Vanilla JavaScript / React (isteğe bağlı) |
| Arka Yüz | Python Flask / Node.js Express (yapılandırılabilir) |
| API İletişimi | Uyumlu User-Agent rotasyonu ile RESTful HTTPS istekleri |
| Dağıtım | Statik dosya barındırma / Serverless mimari uyumlu |
| Lisans | MIT Lisansı |

---

## 📖 Kullanım Kılavuzu

1. FC2 platformunda **herkese açık** olan bir video veya blog gönderisinin bağlantısını kopyalayın
2. URL'yi aracın web arayüzündeki giriş alanına yapıştırın
3. Mevcut meta verileri almak için "Analiz Et" butonuna tıklayın
4. Görüntülenen bilgileri kişisel referans, akademik araştırma, medya analizi veya yasalara uygun dijital medya yönetimi amacıyla kullanın

> ⚠️ Bu araç yalnızca kimlik doğrulama gerektirmeyen, herkese açık içeriklerle çalışır. Ücretli içerikler, üyelere özel içerikler, gizli gönderiler veya yaş kısıtlaması olan içerikler, teknik kısıtlamalar ve uyumluluk gereksinimleri nedeniyle işlenemez.

---

## ⚖️ Uyumluluk Beyanı ve Kullanım Sınırları

Bu proje aşağıdaki ilkelere sıkı sıkıya bağlıdır:

- ✅ FC2 platformunun herkese açık içerik erişim politikalarına ve `robots.txt` yönergelerine saygı duyar
- ✅ Yalnızca kimlik doğrulama gerektirmeyen, herkese açık sayfaların meta verilerini işler
- ✅ Video dosyalarını veya kullanıcı davranış verilerini önbelleğe almaz, iletmez veya saklamaz
- ✅ Yalnızca ticari olmayan araştırma senaryolarıyla sınırlıdır: eğitim, akademik çalışma, dijital beşeri bilimler, medya içerik analizi
- ✅ Platform izin kontrollerini, yaş doğrulamasını veya güvenlik mekanizmalarını atlamaya yönelik hiçbir işlev sunmaz
- ✅ Ücretli içeriğe erişim, yaş doğrulamasını atlama veya indirme zorlama işlevleri sağlamaz
- ✅ FC2 Hizmet Şartları ve veri işleme politikalarına tam uyum sağlar

**Önemli**: Kullanıcılar, kullanımlarının geçerli yasalara (telif hakkı ve kişisel verilerin korunması mevzuatı dahil) ve FC2 Hizmet Şartları'na uygun olduğundan emin olmakla tamamen kendileri sorumludur. Bu aracın geliştiricileri, kötüye kullanım veya uyumsuz kullanım durumunda herhangi bir yasal sorumluluk üstlenmez.

---

## 🤝 Katkıda Bulunma

Topluluk katkılarını memnuniyetle karşılıyoruz! Pull Request göndermeden önce lütfen aşağıdaki adımları izleyin:

1. Depoyu kişisel hesabınıza fork edin
2. Özellik dalı oluşturun: `git checkout -b feat/ozellik-adiniz`
3. Değişikliklerinizi commit edin: `git commit -m 'feat: özellik açıklamanız'`
4. Dalı push edin: `git push origin feat/ozellik-adiniz`
5. GitHub'da, değişikliklerin açık bir açıklaması ve test önerileriyle birlikte bir Pull Request açın

> 📌 Büyük değişiklikler için, teknik yön ve uyumluluk gereksinimleri konusunda hizalanmayı sağlamak adına önce Issues bölümünde tartışmanızı öneririz.

---

## ❓ Sıkça Sorulan Sorular

**S: Bu aracın kullanımı ücretsiz mi?**  
C: Evet, tamamen ücretsizdir. Bu proje MIT açık kaynak lisansı altında yayınlanmaktadır ve öğrenme ile araştırma amaçlı meşru, uyumlu kullanımı destekliyoruz.

**S: Video dosyaları sunucularda geçici olarak saklanıyor mu?**  
C: Hayır. Tüm süreç yalnızca meta veri sorgulamadan ibarettir; hiçbir aşamada medya dosyaları aktarılmaz, önbelleğe alınmaz veya saklanmaz.

**S: Ücretli içerikler veya üyelere özel videolar analiz edilebilir mi?**  
C: Hayır. Teknik uygulanabilirlik ve yasal uyumluluk nedenleriyle yalnızca tamamen herkese açık içerikler desteklenmektedir.

**S: FC2 bloglarına gömülü videolar destekleniyor mu?**  
C: Evet, araç, herkese açık olarak ayarlanmış FC2 blog gönderilerindeki gömülü videoların meta veri sorgulamasını destekler (kimlik doğrulama gerektirmeden erişilebilir olması koşuluyla).

**S: Aracı kullanmak için FC2 hesabına giriş yapmak gerekli mi?**  
C: Hayır. Herkese açık içeriklerin meta veri sorgulaması kimlik doğrulama olmadan işlenir ve kullanıcı hesap bilgileri hiçbir zaman talep edilmez veya saklanmaz.

**S: Hangi FC2 video formatları desteklenmektedir?**  
C: Araç, FC2'deki yaygın herkese açık video formatlarını (FC2 Video videoları ve bloglara gömülü içerikler dahil) destekler. Yeni formatlar sürekli değerlendirilmekte ve teknik olarak mümkün olduğunda entegre edilmektedir.

---

## 📄 Lisans

Bu proje **MIT Lisansı** altında dağıtılmaktadır. Kullanım ve yeniden dağıtım koşullarının tamamı için [LICENSE](LICENSE) dosyasına bakınız.

---

## 🙏 Teşekkürler

- Teknik ilham ve temel bileşenler için açık kaynak topluluğuna
- Bu projenin güvenliğini ve kararlılığını geliştirmek için zaman ayıran tüm katkı sağlayıcılara
- Bu aracı meşru ve uyumlu çerçeveler içinde keşfeden eğitimciler, araştırmacılar ve medya analistlerine

---

## 🔗 Faydalı Bağlantılar

- 📘 [FC2 Geliştirici Bilgileri](https://fc2.com/)
- ⚖️ [FC2 Kullanım Koşulları](https://fc2.com/terms/)
- 🔐 [FC2 Gizlilik Politikası](https://fc2.com/privacy/)
- 🤖 [FC2 API Dokümantasyonu (mevcut ise)](https://fc2.com/)

---

> 🌐 **Çevrimiçi Araç**: [https://twittervideodownloaderx.com/fc2_downloader_tu](https://twittervideodownloaderx.com/fc2_downloader_tu)  
> 🐛 **Sorun Bildir**: [Issues](https://github.com/KullaniciAdiniz/fc2-video-info/issues)  
> 💡 **Özellik Talep Et**: [Discussions](https://github.com/KullaniciAdiniz/fc2-video-info/discussions)

---

*🇹🇷 Türkçe konuşan geliştirici topluluğu ve akademik araştırma ekosistemi için ❤️ ile geliştirildi*