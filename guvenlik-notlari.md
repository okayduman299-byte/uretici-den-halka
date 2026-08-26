# Güvenlik notları

- PII ve sipariş tablolarının anonim SELECT/UPDATE erişimi kapalı tutulur.
- `ureticiler_public` yalnızca vitrin alanları için kullanılır.
- `place_order` oturum gerektirir.
- GitHub Pages üzerinde repository içinden gerçek HTTP `Content-Security-Policy` veya `X-Frame-Options` response header uygulanamaz. Bunlar özel domain/CDN/hosting katmanında ayarlanmalıdır.
