# FLUGEL Island

**GNOME Shell 50** için Dynamic Island: üst çubuğun tamamı ekranın ortasında tek bir siyah kapsüle dönüşür; kapsül
yaylı bir animasyonla canlı etkinliklere, bildirimlere ve sekmeli bir kontrol kartına dönüşür. Siyah-beyaz, karanlık
tema, dokunmatik yüzeyli dizüstü için tasarlandı. English: [README.md](README.md)

![kapsül](docs/kapsul.png)

## Neler yapar
- **Üst çubukta sadece ada.** Saat, pil, Hızlı Ayarlar, takvim, tepsi simgeleri, Etkinlikler ve çalışma alanları
  adanın içinde; Super+S, Super+V ve ses/parlaklık göstergeleri çalışmaya devam eder.
- **Dört durum:** boşta kapsül → kompakt canlı etkinlik → yanında ikinci balonla bölünmüş → genişletilmiş kart.
  Genişlik, yükseklik ve köşe yarıçapı tek bir yayla birlikte değişir; "Animasyonları azalt"a uyar.
- **Canlı etkinlikler** (öncelik sırası ve her biri kapatılabilir): ekran kaydı/mikrofon/kamera, bildirimler, panik,
  sunucu uyarısı, GPU sanal makinesi, çalan medya, hakemlik maçlarım ve canlı skor, anime bölümü, kripto hareketi,
  ses/parlaklık, şarj, kablosuz klavye/fare, haber takip kelimesi.
- **Bildirimler** GNOME afişi yerine adadan animasyonlu afiş olarak açılır.
- **Sekmeler:** Hızlı, Kısayollar, Sistem, Sanal makineler, Kripto (Binance'teki her koin; 1 saatten 1 yıla grafik,
  imleçle inceleme, sürükleyerek ölçme, işaret çizgileri, kapsülde çalan fiyat alarmları), Maçlar (Öne çıkanlar,
  Futbol, Basketbol, Milli, Derbiler, Takımlarım, Özel, CS2; HLTV gibi 0-5 yıldız, favori takımlar üstte, kapsülde
  canlı CS2 raund skoru ve raundu alan takım), Anime ve manga (kapaklı, MAL puanlı; tıklayınca MyAnimeList
  açıklaması, IMDb puanı, yasal izleme bağlantıları), Bildirimler (sunucunun son 24 saati, kategori susturma).
- **Pencere yardımcıları:** resim içinde resim hep sol altta ve son konumu hatırlanır; "Masaüstüne ekle".
- **Dock:** simgeler üzerine gelince büyür. **Dokunmatik yüzey:** kapsülde iki parmakla kaydırınca çalışma alanı değişir.
- **Ayarlar:** 11 sayfalık Adwaita penceresi (her ayar, sayfa sıfırlama, JSON dışa/içe aktarma, otomatik güncelleme,
  Türkçe/English).

## Kurulum
```bash
git clone https://github.com/gok8lp/flugel-island
cd flugel-island
./kur.sh
```
Sonra oturumu kapatıp aç. Veri sekmeleri ana [FLUGEL](https://github.com/gok8lp/flugel) deposundaki
`ust-panel-veri`, `cs2-veri` ve `vm` betiklerini kullanır; onlar olmadan da ada, canlı etkinlikler, bildirimler, PiP ve
kısayollar çalışır.

## Lisans
GPL-3.0-or-later. hacksynth/gnome-dynamic-island (GPL-2.0-or-later) ve HIMURAw/gnome-dynamic-island (GPL-3.0)
çatalıdır — emeği geçenler, veri kaynakları ve markalar: [THIRD_PARTY.md](THIRD_PARTY.md).
