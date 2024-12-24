# Python Veri Yapıları ve Temel Fonksiyonlar

Bu Python kodu, çeşitli veri yapıları ve temel Python fonksiyonlarını kullanarak yapılan işlemleri göstermektedir. Aşağıda her bir bölümün açıklamaları bulunmaktadır.

## Liste İşlemleri
```python
a = ["ahmet", "mehmet", "mustafa", "ayse", "fatma", "mert"]
a.append("veysel")  # Listeye 'veysel' öğesini ekler.
a.remove("mehmet")  # Listeden 'mehmet' öğesini çıkarır.
a.short()  # Bu satır hata verecektir. Doğru komut 'a.sort()' olmalıdır. 
```
Bu bölümde, liste üzerinde bazı temel işlemler yapılmıştır. 
- `append()`: Listeye yeni bir öğe ekler.
- `remove()`: Listeden belirtilen öğeyi kaldırır.
- `sort()`: Listeyi sıralamak için kullanılır, fakat yanlış yazıldığından hata verecektir. 

**Not**: `short()` fonksiyonu geçerli bir Python fonksiyonu değildir, doğru fonksiyon `sort()` olmalıdır.

## String Manipülasyonu
```python
a = "python öğreniyorum"

print(a[1])  # 'p' karakterinin birinci indeksindeki öğeyi yazdırır (yani 'y' karakterini).
print(a[:2])  # 'python öğreniyorum' stringinin başından ilk iki karakterini yazdırır.
print(a[2:])  # 'python öğreniyorum' stringinin 2. indeksinden sonrasını yazdırır.
print(a[0:5])  # 'python öğreniyorum' stringinin başından 5. indekse kadar olan kısmını yazdırır.
```
Bu bölümde bir string üzerinde çeşitli dilimleme işlemleri yapılmaktadır:
- İndeksleme: `a[1]` ifadesi, 1. indeksin karşılık geldiği karakteri alır.
- Dilimleme: `a[:2]`, `a[2:]` ve `a[0:5]` gibi ifadelerle belirli aralıklar seçilir.

## Uzunluk ve Veri Türleri
```python
print(len(a))  # String'in uzunluğunu verir.
```
Burada `len()` fonksiyonu, bir string'in uzunluğunu (karakter sayısını) hesaplar.

## Tuple İşlemleri
```python
b = ("ahmet", "mehmet", "mustafa", "ayse", "fatma", "mert")

print(type(b))  # Tuple veri türünü yazdırır.
print(b[1])  # Tuple'ın 1. indeksindeki öğeyi yazdırır.
```
Bu bölümde bir tuple veri yapısı üzerinde işlemler yapılmıştır:
- `type()`: Verinin tipini belirler. Burada `tuple` tipi döndürülür.
- İndeksleme: Tuple içindeki öğelere indeks kullanılarak erişilebilir.

## Sözlük İşlemleri
```python
sozluk = {"apple": "elma", "car": "araba", "train": "tren"}

print(type(sozluk))  # Sözlük veri türünü yazdırır.
print(sozluk["apple"])  # 'apple' anahtarına karşılık gelen değeri yazdırır.
print(sozluk)  # Tüm sözlüğü yazdırır.

sozluk["pen"] = "kalem"  # 'pen' anahtarı ve 'kalem' değeri eklenir.
```
Bu bölümde bir sözlük üzerinde temel işlemler yapılmaktadır:
- `type()`: Sözlük tipini kontrol eder.
- Anahtara erişim: `sozluk["apple"]` ifadesi, 'apple' anahtarına karşılık gelen değeri döndürür.
- Yeni anahtar ekleme: `sozluk["pen"] = "kalem"` ifadesi, sözlüğe yeni bir anahtar ve değer ekler.

---

Bu README, Python'da temel veri yapıları (liste, tuple, string, sözlük) ve bunlarla yapılan işlemler hakkında temel bir anlayış sağlamaktadır.
