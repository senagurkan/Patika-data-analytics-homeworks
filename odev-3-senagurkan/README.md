# COVID-19 Literatür Analizi – CORD-19 Veriseti

Bu proje, **COVID-19 Open Research Dataset Challenge (CORD-19)** kapsamında yayımlanmış makalelerin temel özelliklerini inceleyerek metin madenciliği ve veri analizine giriş amaçlı gerçekleştirilmiştir.

## 📁 Veri Seti
- Kullanılan veri: `metadata.csv`
- Kaynak: [CORD-19 - Allen Institute for AI](https://www.semanticscholar.org/cord19)

## Proje Amacı
COVID-19 sürecinde yayımlanmış makalelerin **yayın tarihleri**, **lisans türleri**, **başlıklardaki kelime dağılımı** gibi metadatalar üzerinden analiz edilmesi.  
---

## 🔍 Yapılan Analizler

### Veri İncelemesi ve Temizlik
- Verinin boyutu, sütun isimleri ve ilk satırların incelenmesi
- Eksik değer oranlarının hesaplanması ve görselleştirilmesi
- Aşırı eksik değerlere sahip sütunların temizlenmesi

###  Görselleştirmeler
- **Sütunlardaki eksik veri oranları** 
- **Yayın lisansı türlerinin dağılımı**
- **Zamana göre yayın sayısı**
- **Başlıklarda en sık geçen kelimeler** 

### 🧹 Kullanılan Kütüphaneler
```python
pandas, matplotlib, seaborn, wordcloud
```

---

## Dosyalar

| Dosya | Açıklama |
|-------|----------|
| `cord19-analysis.ipynb` | Tüm analizlerin bulunduğu Jupyter Notebook |
| `README.md` | Proje açıklaması |
| (Veri dosyası GitHub'a yüklenmedi) | `.gitignore` ile hariç bırakıldı |

---

## 🗒️ Not
Bu proje, veri analizi ve veri görselleştirme pratiği yapmak için oluşturulmuş temel düzeyde bir çalışmadır. Makine öğrenmesi veya derinlemesine metin madenciliği teknikleri içermemektedir.
