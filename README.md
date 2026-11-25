# Vitrin

Yerel çalışan, gelişmiş **Discord Rich Presence** aracı. Tarayıcıda izlediğin/dinlediğin şeyi ve masaüstünde açık uygulamaları (Spotify, VS Code, Unity, Claude Code, Photoshop…) Discord profilinde gösterir.

Bu depo yalnızca **kurulum dosyalarını ve otomatik güncellemeleri** barındırır.

## Kurulum

1. [Son sürümü indir](https://github.com/SavienWalker/vitrin-releases/releases/latest) → `Vitrin-Setup-x.y.z.exe`
2. Windows "bilinmeyen yayıncı" uyarısı verirse: **Ek bilgi → Yine de çalıştır** (uygulama henüz kod imzalı değil).
3. Tarayıcı uzantısı: aynı sürümdeki `vitrin-extension-x.y.z.zip` dosyasını aç → `chrome://extensions` → Geliştirici modu → **Paketlenmemiş öğe yükle**.

Kurulumdan sonra Vitrin yeni sürümleri kendisi bulur, arka planda indirir ve kurar.

## Gizlilik

- Discord'a yalnızca bilgisayarındaki Discord uygulaması üzerinden (resmi yerel RPC) bağlanır; hesap token'ı kullanılmaz.
- Tarayıcı verisi bilgisayarından çıkmaz: uzantı yalnızca `127.0.0.1` üzerindeki Vitrin uygulamasıyla konuşur.
- Gizli sekmeler, engellenen siteler ve sessiz saatler ayarlardan kapatılabilir.
