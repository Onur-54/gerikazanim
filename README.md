# ♻ GeriKazanım — Tüketimi Ödüllendiriyoruz

> Maya Okulları Sosyal Dersi Projesi

Satın aldığın ürünlerin barkodunu girerek ürün kategorisine göre hesabına para kazanabileceğin interaktif bir web platformu.

---

## 🚀 Nasıl Kullanılır?

1. **Ana Sayfa** → Kazanım oranlarını gözlemle
2. **Barkod Gir** → Ürününün barkodunu ve fiyatını gir, kategoriyi seç
3. **Profilim** → Toplam bakiyeni gör ve para çek

### Canlı Demo

Dosyayı indirip `index.html`'i tarayıcında aç — herhangi bir sunucuya ihtiyaç yok!

---

## 🏷️ Barkod Kategorileri

Her ürün kategorisi, barkodun **ilk hanesiyle** belirlenir:

| İlk Hane | Kategori           | Geri Kazanım |
|----------|--------------------|:------------:|
| **1**    | 🥛 Süt Ürünleri    | %8           |
| **2**    | 🥖 Ekmek & Unlu   | %6           |
| **3**    | 🥤 İçecekler       | %5           |
| **4**    | 🫙 Konserve & Hazır| %7           |
| **5**    | 🧴 Kişisel Bakım   | %10          |
| **6**    | 🧹 Temizlik        | %9           |
| **7**    | 🍫 Atıştırmalık    | %4           |
| **8**    | 🧊 Dondurulmuş    | %6           |

**Örnek:** `1234567890123` → Süt Ürünleri → %8 kazanım

---

## 📁 Proje Yapısı

```
gerikaz/
└── index.html    ← Tek dosya, tüm uygulama burada
```

Sadece `index.html` içerir — harici bağımlılık yok, backend yok, kurulum gerekmez.

---

## ⚙️ Teknik Detaylar

- **Saf HTML / CSS / JavaScript** — framework yok
- **Google Fonts:** Space Grotesk, Unbounded
- **Veri:** Oturum içi (localStorage kullanılmıyor; sayfa yenilenince sıfırlanır)
- **GitHub Pages uyumlu** — `index.html` doğrudan yayınlanabilir

### GitHub Pages'e Yükleme

1. Bu repoyu fork'la veya klonla
2. `Settings → Pages → Branch: main → / (root)` seç
3. Birkaç dakika bekle → sitenin yayında!

---

## 👥 Geliştiriciler

Bu web sitesi **Maya Okulları** için aşağıdaki öğrenciler tarafından geliştirilmiştir:

- **Onur BOZOK**
- **Göktürk ŞİMŞEK**
- **Yiğit ÇETİN**
- **Ozan ŞENTEKİN**

---

© 2026 GeriKazanım · Maya Okulları Sosyal Dersi Projesi
