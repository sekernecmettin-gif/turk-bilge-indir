# TÜRK BİLGE — İndirme

Türkiye Yüzyılı Maarif Modeli'ne uygun **9–12. sınıf lise tarih dersi etkileşimli harita programı**.
Öğretmenler için akıllı tahtada kullanılan tarih atlası.

> Program yapımcısı: **Tarih Öğretmeni Necmettin ŞEKER**

## Kurulum dosyaları

En son sürümü sağdaki **[Releases](../../releases/latest)** bölümünden indirin:

| İşletim sistemi | Dosya | Kurulum |
|---|---|---|
| **Pardus / Debian** (ETAP dahil) | `turk-bilge_<sürüm>_amd64.deb` | Dosyaya çift tıklayıp **Pardus Paket Kurucu** ile "Kur"a basın. |
| **Windows** | `TurkBilge-<sürüm>.exe` | Kurulum gerektirmez, çift tıklayınca açılır. |

## Kullanım

- Kurulumdan sonra program uygulama menüsünde **TÜRK BİLGE** adıyla yer alır.
- Okul ağındaki diğer tahta ve bilgisayarlardan erişmek için tarayıcıya `http://<sunucu-ip>:8090` yazın.
- İnternetsiz ortamlarda da bütün haritalar çalışır; yalnızca "bugünkü görünüm" uydu/sokak katmanı internet ister.

## Lisans ve kaynaklar

Program kodu telif hakkıyla korunmaktadır; izinsiz çoğaltılamaz ve dağıtılamaz.
Harita sınır verileri *historical-basemaps* (André Ourednik, GPL-3.0), altlık *Natural Earth* (kamu malı) kaynaklıdır.

---

## Kullanım Kılavuzu

### Kurulum — Pardus / Debian (ETAP)
1. `turk-bilge_<sürüm>_amd64.deb` dosyasını indirin.
2. Dosyaya **çift tıklayın**; Pardus Paket Kurucu açılır.
3. **Kur**'a basın (gerekirse yönetici parolası; ETAP'ta `etapadmin`).
4. Kurulum bitince program kendiliğinden başlar.

### Kurulum — Windows
1. `TurkBilge-<sürüm>.exe` dosyasını indirin.
2. Çift tıklayın; kurulum gerektirmez, doğrudan açılır.
3. "Bilinmeyen yayımcı" uyarısında **Ek bilgi → Yine de çalıştır**.

### Programı açma
- **Pardus:** Uygulama menüsünde **TÜRK BİLGE** simgesi.
- **Windows:** indirdiğiniz dosyaya çift tıklayın.
- **Başka tahtadan:** tarayıcıya `http://<sunucu-ip>:8090`.

### Ekranı tanıyalım
- **Sol panel:** sınıf (9–12), ünite ve konu seçimi.
- **Üstteki yıl / alttaki zaman çubuğu:** haritanın dönemi; yılı ileri-geri alın.
- **Sağ araç çubuğu:** kalem, fosforlu, ok, silgi, renkler, katmanlar, tam ekran.
- **Haritadaki işaretler:** tıklayınca bilgi kartı ve o yerin bugünkü görünümü açılır.

### Kısayol tuşları
| Tuş | İşlev | Tuş | İşlev |
|---|---|---|---|
| → / ← | Sonraki / önceki konu | K | Kalem |
| ↑ / ↓ | Sonraki / önceki yıl | F | Fosforlu kalem |
| M | Menü aç/kapat | O | Ok |
| A | Açıklama göster/gizle | S | Silgi |
| T | Tam ekran | Ctrl+Z | Geri al |
| G | Bugünkü görünüm | Esc | Gezinme kipi |
| / veya Ctrl+K | Akıllı arama | | |

### Sık sorulanlar
- **"Bugünkü görünüm" boş:** bu katman internet ister; tarihî haritalar internetsiz de çalışır.
- **Başka tahtadan açılmıyor:** adresi doğru yazdığınızdan ve iki tahtanın aynı ağda olduğundan emin olun.
