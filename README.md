# Luminous Sezon Takvimi

Bu, Luminous Robotics Team (Takım 9233) için hazırlanmış statik bir web sayfasıdır. GitHub Pages üzerinde ücretsiz barındırılır.

## Kurulum (ilk seferde)

1. GitHub'da yeni bir repo oluştur (örn. `luminous-takvim`), **Public** olarak.
2. Bu klasördeki `index.html` ve `events.json` dosyalarını "Add file → Upload files" ile reponun ana dizinine yükle.
3. Repo **Settings → Pages** sayfasına git, "Branch" olarak `main` ve `/ (root)` seç, Save'e bas.
4. Birkaç dakika sonra siten şu adreste yayında olacak: `https://KULLANICIADI.github.io/luminous-takvim/`
5. `events.json` dosyasını GitHub üzerinde aç, en üstteki `"repo": "KULLANICIADI/luminous-takvim"` satırını kendi kullanıcı adın ve repo adınla güncelle, kaydet (Commit). Bu, sayfadaki "+ Etkinlik ekle" düğmesinin doğru yere gitmesini sağlar.

## Bir etkinlik eklemek / düzenlemek

1. Sayfadaki **"+ Etkinlik ekle"** düğmesine bas (ya da doğrudan GitHub'da `events.json` dosyasını aç).
2. İlgili ayın `events` listesine yeni bir satır ekle, örnek:
   ```json
   { "day": "15", "dow": "Cum", "cat": "kayit", "title": "Yeni etkinlik başlığı", "desc": "İsteğe bağlı açıklama", "time": "" }
   ```
3. `cat` alanı şunlardan biri olmalı: `kayit`, `odul`, `kit`, `yarisma` (renk kodunu belirler).
4. Sağ üstteki "Commit changes" ile kaydet. Sayfa bir sonraki açılışta otomatik güncellenir.

Kodla ilgili bir sorun yaşarsan dosyayı olduğu gibi Claude'a gönderip yardım isteyebilirsin.
