# Finans Takip

Gelir, sabit/düzenli gider, tekil gelir-gider, kota ve yıllık birikim planını takip eden basit bir PWA (telefon uygulaması gibi, çevrimdışı çalışır).

## Telefona kurma
1. Yayınlanan linki telefonda aç.
2. **Android (Chrome):** menü → "Ana ekrana ekle" / "Uygulamayı yükle".
3. **iPhone (Safari):** Paylaş → "Ana Ekrana Ekle".

Veriler tamamen telefonun içinde tutulur (localStorage), internet gerekmez.

## Geliştirme
Yerelde çalıştırmak için:
```
python3 -m http.server 8801
```
ardından `http://127.0.0.1:8801/index.html`.
