# Luminous Sezon Takvimi

Bu, Luminous Robotics Team (Takım 9233) için hazırlanmış statik bir web sayfasıdır. GitHub Pages üzerinde ücretsiz barındırılır.

## Bir etkinlik eklemek / düzenlemek

1. Sayfadaki **"+ Etkinlik ekle"** düğmesine bas (ya da doğrudan GitHub'da `events.json` dosyasını aç).
2. İlgili ayın `events` listesine yeni bir satır ekle, örnek:
   ```json
   { "day": "15", "dow": "Cum", "cat": "kayit", "title": "Yeni etkinlik başlığı", "desc": "İsteğe bağlı açıklama", "time": "" }
   ```
3. `cat` alanı şunlardan biri olmalı: `kayit`, `odul`, `kit`, `yarisma` (renk kodunu belirler).
4. Sağ üstteki "Commit changes" ile kaydet. Sayfa bir sonraki açılışta otomatik güncellenir.

