# taxiguard-config

TaxiGuard uygulamasının uzaktan tarife yapılandırması. Uygulama açılışta
`tariffs.json`'u buradan çeker (`remoteConfigUrl`), böylece taksi tarifesi veya
geçiş ücreti değiştiğinde mağaza güncellemesi beklenmeden sahaya iner.

## Nasıl güncellenir

Tarife değişiklikleri **PR ile** gelir — doğrudan `main`'e yazılmaz. Haftalık
bir izleyici ajan İBB/haber kaynaklarını tarar; makul bir değişiklik sezerse
iki kaynakla çapraz doğrulayıp bir PR açar. İnsan onayı (merge) olmadan hiçbir
rakam sahaya çıkmaz — yanlış okunmuş bir tarife dürüst şoförü suçlayabileceği
için bu kapı bilinçlidir.

## Şema

`schemaVersion` + `tariffVersion` (tarih) taşır. Uygulama yalnız şeması uyumlu
ve `tariffVersion`'ı kurulu olandan yeni/eşit config'i kabul eder (sürüm
gerilemesi reddedilir). Kaynak şema: antiscam-taxi/src/config/tariffs.json.
