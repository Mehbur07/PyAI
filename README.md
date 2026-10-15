# PyAI
Ben ve arkadaşımın yaptığı ilk chatbot

## Kurulum

PyAI tek bir dosyadan oluşur: **`PyAI.exe`**. Kurulum gerekmez, Python yüklü olmasına da gerek yoktur.

1. [`PyAI.exe`](PyAI.exe) dosyasını indir.
2. İstediğin bir klasöre koy.
3. Çift tıklayıp aç.

## Açılınca otomatik oluşanlar

`PyAI.exe` ilk açıldığında gereken her şeyi kendisi oluşturur, elle bir şey yapmana gerek yoktur:

| Ne oluşur | Nerede | Ne işe yarar |
|---|---|---|
| `sohbetler/` klasörü | `PyAI.exe` ile aynı klasörde | Her sohbet, tarih ve saatle adlandırılmış ayrı bir JSON dosyası olarak buraya kaydedilir (ör. `sohbet_2026-10-09_15-01-33.json`). |
| `memory.json` | `PyAI.exe` ile aynı klasörde | PyAI'ın öğrendiği soru–cevapları saklar. |
| Kısayol | Masaüstü | PyAI'ı masaüstünden hızlıca açmanı sağlar. |

Örnek bir sohbet dosyası:

```json
[
    { "user": "merhaba", "ai": "sana da merhaba" },
    { "user": "adın ne", "ai": "Ben PyAI dünyayı ele geçireceğim" }
]
```

## Notlar

- Sohbetlerin ve PyAI'ın öğrendikleri sadece senin bilgisayarında, `PyAI.exe`'nin bulunduğu klasörde tutulur.
- Windows SmartScreen uyarı verirse **Ek bilgi → Yine de çalıştır** ile açabilirsin.
