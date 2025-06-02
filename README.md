# 🧠 Knapsack Problem Solver

Bu proje, **0/1 Knapsack Problem** için farklı büyüklükteki veri setleri (40, 300, 1000, 10000) üzerinde **optimal çözümler** üreten bir Python uygulamasıdır. Çözümler Dynamic Programming algoritmasıyla elde edilmektedir.

## 📦 Veri Setleri

Proje kapsamında aşağıdaki veri setleri kullanılmıştır:

- `ks_40_0.txt`
- `ks_300_0.txt`
- `ks_1000_0.txt`
- `ks_10000_0.txt`

Tüm dosyalar şu formatta yapılandırılmıştır:

```
<item_count> <capacity>
<value_1> <weight_1>
<value_2> <weight_2>
...
```

## 🚀 Kullanılan Yöntem:

- **Dynamic Programming (DP):** Küçük ve orta boy veri setlerinde optimal çözüm sağlar.
- Büyük veri setleri için bellek dostu çözümler uygulanmıştır.

## 📊 Sonuçlar

Tüm veri setleri çözülmüş ve sonuçlar `knapsack_summary.xlsx` adlı Excel dosyasına aşağıdaki formatta eklenmiştir:

## 🧪 Nasıl Çalıştırılır?

1. Gerekli kütüphaneleri kur:
```bash
pip install openpyxl
```

2. Notebook'u aç ve çalıştır:
```bash
jupyter notebook knapsack_solver.ipynb
```
3. Sonuçlar otomatik olarak `knapsack_summary.xlsx` dosyasına yazılır.

📌 Bu proje bir ders ödevi kapsamında gerçekleştirilmiştir.

