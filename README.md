# Türkiye Halı Yıkama Fiyatları 2026

Türkiye'nin 81 ilinde ve 682 ilçesinde halı yıkama firmalarının m² fiyatları: 24 halı türü için en düşük, ortalama ve en yüksek fiyat, fiyatın kaç firmadan derlendiği ve il, ilçe bazında firma sayıları. Veri Kasım 2026'da [Halı Yıkama Fabrikaları](https://haliyikamafabrikalari.com) dizinindeki **4.561 firmadan**, fiyat listesi yayımlayan **421 firmanın** fiyatlarıyla hazırlandı.

Güncel rakamlar, ilçe ilçe firma listeleri ve halı ölçüsüne göre tutar hesabı sitededir: [haliyikamafabrikalari.com/hali-yikama-fiyatlari](https://haliyikamafabrikalari.com/hali-yikama-fiyatlari)

## Öne çıkan rakamlar (Kasım 2026)

- Türkiye'de **makine halısının m² yıkama fiyatı 50–300 TL, ortalaması 116 TL** (413 firmanın fiyat listesinden).
- En pahalı tür **ipek halı**: ortalama 735 TL/m², en yüksek 2.000 TL/m².
- 4 m² (160 × 230 cm) makine halısı ortalama 464 TL, 6 m² (200 × 300 cm) ortalama 696 TL tutar; servis ücreti hariç.
- Makine halısında ortalaması en düşük iller (en az 3 firmanın fiyatıyla): Malatya 85 TL, Kayseri 90 TL, Konya 92 TL, Kahramanmaraş 93 TL, Erzurum 94 TL.
- Ortalaması en yüksek iller: İstanbul 133 TL, Antalya 126 TL, Kocaeli 111 TL, Muğla 110 TL, İzmir 110 TL.

### Türkiye geneli, halı türüne göre m² fiyatı

| Halı türü | Fiyat veren firma | En düşük (TL/m²) | Ortalama (TL/m²) | En yüksek (TL/m²) |
|---|---:|---:|---:|---:|
| Makine halısı | 413 | 50 | 116 | 300 |
| Akrilik halı | 353 | 50 | 163 | 1150 |
| Shaggy halı | 387 | 75 | 163 | 300 |
| Peluş halı | 322 | 50 | 173 | 350 |
| Apex halı | 308 | 50 | 117 | 300 |
| Frize (floşlu) halı | 318 | 50 | 197 | 400 |
| Bukle halı | 315 | 50 | 180 | 650 |
| İskandinav halı | 321 | 50 | 192 | 700 |
| Step halı | 364 | 75 | 239 | 600 |
| Yün halı (makine) | 347 | 100 | 198 | 500 |
| Yün halı (el dokuma) | 320 | 150 | 333 | 650 |
| Bambu halı | 369 | 100 | 265 | 600 |
| Viskon halı | 341 | 100 | 252 | 550 |
| İpek halı | 358 | 140 | 735 | 2000 |
| Jüt halı | 325 | 85 | 225 | 490 |
| Hasır halı | 326 | 85 | 214 | 500 |
| Sisal halı | 319 | 85 | 214 | 600 |
| El dokuma halı | 352 | 100 | 288 | 800 |
| Patchwork halı | 344 | 140 | 269 | 550 |
| Tafting (handtuft) halı | 314 | 200 | 280 | 600 |
| Kilim (makine) | 321 | 85 | 165 | 400 |
| Kilim (el dokuma) | 321 | 120 | 271 | 1000 |
| Seccade | 314 | 50 | 164 | 300 |
| Yolluk | 314 | 85 | 164 | 600 |

Halı türlerinin ayrı fiyat sayfaları: [makine halısı](https://haliyikamafabrikalari.com/hali-yikama-fiyatlari/makine-halisi), [shaggy halı](https://haliyikamafabrikalari.com/hali-yikama-fiyatlari/shaggy-hali), [yün halı](https://haliyikamafabrikalari.com/hali-yikama-fiyatlari/yun-hali-makine), [ipek halı](https://haliyikamafabrikalari.com/hali-yikama-fiyatlari/ipek-hali), [bambu halı](https://haliyikamafabrikalari.com/hali-yikama-fiyatlari/bambu-hali). Ölçüye göre tutar: [halı yıkama fiyat hesaplama](https://haliyikamafabrikalari.com/hali-yikama-fiyat-hesaplama), standart ölçüler: [halı ölçüleri](https://haliyikamafabrikalari.com/hali-olculeri).

## Dosyalar

| Dosya | Satır | İçerik |
|---|---:|---|
| `turkiye_hali_yikama_fiyatlari.csv` | 24 | Türkiye geneli, halı türüne göre |
| `il_hali_yikama_fiyatlari.csv` | 1.093 | İl ve halı türüne göre |
| `ilce_hali_yikama_fiyatlari.csv` | 3.233 | İlçe ve halı türüne göre |
| `il_firma_sayilari.csv` | 81 | İldeki firma sayısı ve fiyat veren firma sayısı |
| `ilce_firma_sayilari.csv` | 682 | İlçede bulunan firma sayısı |

Dosyalar UTF-8, virgülle ayrılmış (CSV). Sütunlar:

- `il`, `ilce`, `hali_turu`
- `birim`: fiyatın birimi (bütün türlerde TL/m²)
- `fiyat_veren_firma`: rakamın kaç firmanın fiyat listesinden derlendiği
- `en_dusuk_tl`, `ortalama_tl`, `en_yuksek_tl`: m² yıkama fiyatı, Türk lirası
- `firma_sayisi`: dizindeki onaylı firma sayısı
- `kaynak_sayfa`: rakamın güncel hâlinin ve firma listesinin bulunduğu sayfa

## Yöntem

- Fiyatlar, halı yıkama firmalarının kendi web sitelerinde ve fiyat listelerinde yayımladığı ya da dizine bildirdiği m² fiyatlarıdır. Servis (alım-teslim) ücreti dahil değildir.
- Yalnız dizinde yayında olan (onaylı) firmalar sayılır. Fiyatı olmayan firma, fiyat sütunlarına girmez; firma sayılarına girer.
- **Ortalama, en az 3 firmanın fiyatı varsa** verilir; daha az firmada `ortalama_tl` boştur, en düşük ve en yüksek fiyat yine yazılır.
- İlçe satırlarına, ilçede bulunan firmalarla birlikte o ilçeye servis veren komşu ilçe firmaları da girer (ilçe sayfasındaki listeyle aynı kapsam). Bu yüzden bir ildeki ilçe satırlarının toplamı il satırından büyük olabilir.
- Rakamlar haliyikamafabrikalari.com sayfalarında gösterilen rakamlarla aynı hesapla üretilmiştir. Firmalar fiyatlarını değiştirebilir; güncel rakam için `kaynak_sayfa` sütunundaki sayfaya bakın.
- Veri tarihi: 25 Kasım 2026.

## Lisans ve atıf

[Creative Commons Atıf 4.0 Uluslararası (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.tr). Veriyi haber, araştırma, blog ya da uygulamada serbestçe kullanabilirsiniz; tek şart kaynağı bağlantısıyla göstermektir:

> Kaynak: [Halı Yıkama Fabrikaları](https://haliyikamafabrikalari.com), Türkiye Halı Yıkama Fiyatları 2026.

Atıf biçimi:

```
Halı Yıkama Fabrikaları (2026). Türkiye Halı Yıkama Fiyatları 2026 [Veri seti]. https://haliyikamafabrikalari.com/hali-yikama-fiyatlari
```

İletişim: destek@haliyikamafabrikalari.com

---

## English summary

**Turkey Carpet Cleaning Prices 2026.** Per-square-metre carpet cleaning prices from carpet cleaning companies in all 81 provinces and 682 districts of Turkey: minimum, average and maximum price for 24 carpet types, the number of companies each figure is based on, and company counts per province and district. Compiled in November 2026 from the price lists of 421 companies out of 4,561 listed on [Halı Yıkama Fabrikaları](https://haliyikamafabrikalari.com), Turkey's carpet cleaning price comparison directory.

- Machine-made carpet: 50–300 TRY per m², average 116 TRY (413 companies). Silk carpet: average 735 TRY per m².
- Prices exclude pick-up and delivery fees. Averages are given only where at least 3 companies publish a price.
- Columns: `il` province, `ilce` district, `hali_turu` carpet type, `birim` unit, `fiyat_veren_firma` companies with a price, `en_dusuk_tl` / `ortalama_tl` / `en_yuksek_tl` minimum / average / maximum price in TRY, `firma_sayisi` number of companies, `kaynak_sayfa` source page with current prices.
- License: CC BY 4.0. Please credit "Halı Yıkama Fabrikaları (haliyikamafabrikalari.com)" with a link.
