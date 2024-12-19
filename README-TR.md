# ngx-dynamic-realip

Nginx için dinamik gerçek IP işleme modülü. `CF-Connecting-IP` ve `X-Real-IP` başlıklarını öncelikli olarak kontrol eder.

## Özellikler

- **Dinamik Başlık İşleme:** `CF-Connecting-IP` başlığını öncelikli olarak kontrol eder, ardından `X-Real-IP`'ye geçiş yapar.
- **Yedekleme Mantığı:** Eğer başlıklar mevcut değilse, varsayılan olarak `remote_addr` kullanılır.
- **CDN Uyumluluğu:** Cloudflare ve diğer proxy/CDN servisleriyle uyumlu.

## Kurulum

1. Depoyu klonlayın:
   ```bash
   git clone https://github.com/kullaniciadi/ngx-dynamic-realip.git
