# ngx-dynamic-realip

Dynamic real IP handling for Nginx with prioritized `CF-Connecting-IP` and `X-Real-IP` headers.

## Features

- **Dynamic Header Processing:** Automatically prioritizes `CF-Connecting-IP` over `X-Real-IP`.
- **Fallback Logic:** Defaults to `remote_addr` if no headers are available.
- **CDN Compatibility:** Designed for use with Cloudflare and other proxy/CDN services.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ngx-dynamic-realip.git
