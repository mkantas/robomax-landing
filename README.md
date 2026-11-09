# Robot Süpürge Landing Page

Dreame F10 ürün sayfasından esinlenerek hazırlanmış, **satışsız** (sadece tanıtım) tek sayfalık landing page şablonu.

## Klasör Yapısı

```
robot-vacuum-landing/
├── index.html          # Ana sayfa
├── css/style.css       # Stiller
├── js/main.js          # Mobil menü + scroll animasyonları
├── images/             # Görsel slotları (SVG placeholder)
│   ├── hero.jpg
│   ├── suction.jpg
│   ├── dustbin.jpg
│   ├── water-tank.jpg
│   ├── carpet.jpg
│   ├── battery.jpg
│   ├── navigation.jpg
│   ├── voice.jpg
│   └── app.jpg
└── README.md
```

## Görselleri Değiştirme

`images/` klasöründeki `.jpg` placeholder dosyalarını kendi görsellerinizle değiştirin.
İki yol var:

1. **Aynı dosya adını koruyun:** örn. `hero.jpg` yerine kendi `hero.jpg` dosyanızı koyup `index.html` içindeki `src="images/hero.jpg"` ifadesini `src="images/hero.jpg"` olarak güncelleyin.
2. **Dosyayı overwrite edin:** placeholder'ın üzerine aynı isimle (`.jpg`) kendi SVG/PNG'nizi yazın.

Görsel slotları:
- `hero.jpg` — Ana hero görseli (ürün)
- `suction.jpg` — Emiş gücü bölümü
- `dustbin.jpg` — 2'si 1 arada / toz kutusu
- `water-tank.jpg` — Su haznesi (opsiyonel ayrı görsel)
- `carpet.jpg` — Halı bakımı
- `battery.jpg` — Pil / şarj
- `navigation.jpg` — Navigasyon
- `voice.jpg` — Sesli kontrol
- `app.jpg` — Uygulama ekranı

## Metinleri Değiştirme

`index.html` içindeki `[Marka]`, `[Ürün Adı]` ve sayısal değerleri (Pa, mAh, ml, mm, dk, m²) kendi ürününüze göre güncelleyin. Tüm düzenlenebilir alanlar köşeli parantez `[...]` ile işaretlenmiştir.

## Renk / Tema

`css/style.css` dosyasının başındaki `:root` değişkenlerinden renkleri, fontları ve yarıçapları değiştirebilirsiniz.

## Önizleme

`index.html` dosyasını tarayıcıda açmanız yeterlidir (internet bağlantısı yalnızca Google Fonts için gereklidir).
