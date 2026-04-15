# Kick Clipper — TOSPİK Limited Edition

Kick.com için maksimum kalitede klip, VOD ve HLS indirici. Tek dosya kurulum, sade arayüz, hızlı kuyruk yönetimi.

---

## Kurulum

1. `KickClipper-Setup.zip` dosyasını indir.
2. Sağ tık → **Tümünü çıkart** ile ZIP'i aç.
3. İçinden çıkan [`KickClipper-Setup-LIMITED-EDITION-TOSPIK.exe`](https://github.com/Fatihstf/Tospik-Kick-Clipper/releases/tag/v1.0.1) dosyasına çift tıkla. 
4. Windows Defender SmartScreen uyarısı çıkarsa: **Daha fazla bilgi → Yine de çalıştır**.
5. Kurulum sihirbazını takip et, kurulum klasörünü seçebilirsin (varsayılan da olur).
6. Bittiğinde masaüstünde **Kick Clipper** kısayolu oluşur.

> **Not:** İlk açılışta uygulama sistem tepsisinde de görünür (sağ alt tepsi). Pencereyi kapatınca arka planda çalışmaya devam eder; tamamen çıkmak için tepsi ikonuna sağ tıklayıp **Çıkış**'ı seç.

---

## Kullanım

### 1. Tek bir link indirmek (klip / VOD / m3u8)

![Link sekmesi](images/link-tab.png)

1. Üst menüden **Link** sekmesine geç.
2. Kick klip URL'si, klip ID'si veya doğrudan `.m3u8` bağlantısı yapıştır.
   - Örnek: `https://kick.com/streamer/clips/clip_xxxxx`
   - Örnek: `https://kick.com/video/xxxxx`
3. **Analiz Et** butonuna bas.
4. Çıkan kartta:
   - **Klip** ise direkt **Kuyruğa ekle**.
   - **VOD/HLS** ise önce kalite seç (Source = maksimum kalite önerilir), sonra **Kuyruğa ekle**.
5. İlk indirmende klasör seçici otomatik açılır — videoların kaydedileceği klasörü seç.

### 2. Bir kanalın tüm kliplerini / VOD'larını listelemek

![Kanal - Klipler](images/kanal-klipler.png)

![Kanal - VOD'lar](images/kanal-vod.png)

1. Üst menüden **Kanal** sekmesine geç.
2. Kanal adını yaz (örn. `tospik`) ve **Kanalı Aç** bas.
3. Üstten **Klipler** veya **VOD'lar** sekmesini seç.
4. Klipler için filtre çubuğundan **Öne çıkan / 1 Ay / Tümü** seçeneklerini değiştirebilirsin.
5. Kartlara tıklayıp seç (sağ üst köşedeki tik kutusu yeşil olur).
6. **İndir (N)** butonuna bas — hepsi sırayla kuyruğa düşer.

> **İpucu:** Sağ üstteki **Tarih** butonuyla klipleri yeniye/eskiye göre sıralayabilirsin.

### 3. Kuyruk yönetimi

- Sağ paneldeki **İndirme Kuyruğu**'ndan ilerleme, hız ve kalan süreyi izleyebilirsin.
- Bir indirmenin yanındaki:
  - ⏸ **Duraklat** — geçici durdurur (henüz başlamadıysa)
  - ✕ **İptal** — başlamış indirmeyi keser
  - 📁 **Aç** — biten dosyayı klasörde gösterir
- Üstteki **Eşzamanlı: N** ayarıyla aynı anda kaç indirmenin koşacağını belirleyebilirsin (1–8 arası).

### 4. Öncelik ayarı

Üst bardaki **Öncelik** seçicisi (Yüksek / Normal / Düşük) — yeni eklenen indirmelerin kuyrukta hangi sırayla işleneceğini belirler.

---

## Özellikler

- ✅ Maksimum kalite (Source) HLS / VOD desteği
- ✅ Klip toplu indirme (kanal başına yüzlerce klip)
- ✅ Aynı isimli kliplerde otomatik `(1)`, `(2)` ekleme — üzerine yazmaz
- ✅ Klip kartında yayın tarihi, VOD kartında saat bilgisi
- ✅ Tarihe göre sıralama
- ✅ Kuyruk kalıcı, paralel indirme (1–8)
- ✅ Sistem tepsisinde arka plan modu
- ✅ Bağımlılık yok — ffmpeg dahil tek paket

---

## Sorun Çözme

| Sorun | Çözüm |
|---|---|
| **SmartScreen "Tanınmayan uygulama" uyarısı** | "Daha fazla bilgi → Yine de çalıştır". İmza yok, normal. |
| **İndirme başlamıyor** | Kuyrukta beklediğinden emin ol; eşzamanlı limiti yetersizse arttır. |
| **VOD bulunmuyor / 404** | Yayın silinmiş olabilir veya sadece abonelere açık. |
| **Klasör seçilmedi hatası** | İndir butonuna tıklayınca açılan pencereden klasör seç. |
| **Antivirüs karantinaya aldı** | İmzasız `.exe` olduğu için bazı AV'ler false-positive verir; istisna ekleyebilirsin. |

---

## İletişim & Destek

- 💬 **Discord**: https://discord.gg/tospik
- 🎮 **Kick**: https://kick.com/tospik

---

**TOSPİK Limited Edition** © 2026 — Kick.com clip & VOD downloader
