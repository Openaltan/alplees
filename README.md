<p align="center">
  <a href="https://github.com/Openaltan/alplees/releases/latest">
    <img src="./assets/readme/alplees-hero-centered.svg" alt="Alplees - AI destekli sesle yazma" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/Openaltan/alplees/releases/latest">
    <img alt="Son sürüm" src="https://img.shields.io/github/v/release/Openaltan/alplees?label=son%20s%C3%BCr%C3%BCm&style=for-the-badge&color=ff7a3d&labelColor=0b0b10" />
  </a>
  <a href="https://github.com/Openaltan/alplees/releases">
    <img alt="İndirmeler" src="https://img.shields.io/github/downloads/Openaltan/alplees/total?label=indirme&style=for-the-badge&color=ffb066&labelColor=0b0b10" />
  </a>
  <a href="https://github.com/Openaltan/alplees/releases/latest">
    <img alt="Windows 10+" src="https://img.shields.io/badge/Windows-10%2B-1c1c28?style=for-the-badge&logo=windows11&logoColor=ffb066&labelColor=0b0b10" />
  </a>
  <a href="https://github.com/Openaltan/alplees/releases/latest">
    <img alt="Release repo - installer paketleri" src="https://img.shields.io/badge/release%20repo-installer%20paketleri-14141c?style=for-the-badge&labelColor=0b0b10&color=14141c" />
  </a>
</p>

<h3 align="center">Konuşmanı yakalar, metne dönüştürür, yazı diline taşır.</h3>

<p align="center">
  Alplees; koyu, sakin ve hızlı bir masaüstü deneyimi içinde sesli yazma,
  profesyonel dikte, çeviri, özel sözlük ve asistan akışlarını bir araya getirir.
</p>

<p align="center">
  <a href="https://github.com/Openaltan/alplees/releases/latest">
    <img alt="Alplees'i indir" src="https://img.shields.io/badge/Alplees%27i%20indir-Releases-ff7a3d?style=for-the-badge&logo=github&logoColor=1a1208&labelColor=ffb066" />
  </a>
</p>

## Alplees Ne Yapar?

| Özellik | Açıklama |
| --- | --- |
| **Sesle Yazma** | Konuşmanı yerel Whisper akışıyla metne dönüştürür. |
| **Profesyonel Dikte** | Dağınık konuşma dilini daha okunur ve düzenli yazı diline taşır. |
| **Normal / Doğal Mod** | Cümle yapısını bozmadan hafif temizlik ve noktalama yapar. |
| **Akıllı Sözlük** | Özel terimleri, marka adlarını ve teknik ifadeleri daha doğru korur. |
| **Onaylı Öğrenme** | Yeni terimleri otomatik fark eder, sözlüğe eklemeden önce kullanıcıya sorar. |
| **Asistan** | Seçili metni düzenleme, ekrandaki durumu anlama ve pratik yanıt üretme akışlarını destekler. |

## Son Sürümde Öne Çıkanlar

`v0.2.3`, profesyonel dikte ve akıllı sözlük davranışını daha güvenilir hale getirir:

- Profesyonel mod artık soru, itiraz, talep ve örnek verme niyetini korur; soruları cevap gibi kesin hükme çevirmemesi için güçlendirildi.
- Özellik ve kısayol anlatımlarında eşleştirme korunur; bir özelliğin kısayolu başka bir özelliğe taşınmaz.
- Sözlük terimleri yalnızca metinde bağlamı varsa düzeltme için kullanılır; sözlükteki kelimelerin çıktıya sızması engellendi.
- OpenRouter gibi yerleşik teknik terimler artık tekrar tekrar "sözlüğe ekleyeyim mi?" önerisi üretmez.
- Kullanıcının dikte sonrası yaptığı özel terim düzeltmelerini yakalama akışı iyileştirildi.
- Uzun profesyonel diktelerde içerik kaybı riskini azaltmak için çıktı bütçesi ve yerel model bağlamı artırıldı.
- Asistan, aktif tarayıcı URL'sini ve TikTok video kimliğini bağlam olarak algılayabilecek ilk altyapıya kavuştu.

## İndir

En güncel Windows kurulum dosyası GitHub Releases üzerinden yayınlanır:

<p>
  <a href="https://github.com/Openaltan/alplees/releases/latest">
    <img alt="Son release'i aç" src="https://img.shields.io/badge/Son%20release%27i%20a%C3%A7-GitHub%20Releases-ff7a3d?style=for-the-badge&logo=github&logoColor=1a1208&labelColor=ffb066&color=ff7a3d" />
  </a>
</p>

## Görsel Kimlik

Alplees arayüzü koyu zemin, yumuşak panel ayrımları ve sıcak turuncu vurgular üzerine kurulur.

| Rol | Renk |
| --- | --- |
| Ana zemin | `#0b0b10` |
| Panel | `#14141c` |
| İkincil panel | `#1c1c28` |
| Ana vurgu | `#ff7a3d` |
| Sıcak vurgu | `#ffb066` |
| Metin | `#f3f3f7` |

## Not

> Sesle yazma uygulaması. Bu repo uygulama kaynak kodunu değil, sürüm (release) dosyalarını barındırır.
> Kurulum dosyaları, blockmap ve otomatik güncelleme metadata dosyaları GitHub Releases üzerinden yayınlanır.
