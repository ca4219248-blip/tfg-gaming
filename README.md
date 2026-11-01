# TFG GAMING — website

Ek single-file website: videos, gear picks (affiliate), UPI support, brand collab enquiries aur newsletter.

## Kaise edit karein
Sab kuch `index.html` ke andar ek hi block me hai — dhoondho:

    const CONFIG = { ... }

- **UPI ID**: `CONFIG.support.upiId` (aur QR bhi update karna ho to `qrImage` me apna QR image URL daalo)
- **Affiliate links**: `CONFIG.products` me har product ka `url` apne affiliate link se badlo
- **Videos**: `CONFIG.videos` — title, views, date, url (thumb me YouTube thumbnail URL daal sakte ho)
- **Social links**: `CONFIG.socials`
- **Rate card**: `CONFIG.rates`
- **Media kit numbers**: `CONFIG.collabStats` (asli numbers daalo, guess nahi)
- **Owner panel passphrase**: `CONFIG.admin.passphrase` — publish se pehle badal do
- **Forms**: `CONFIG.forms.endpoint` me free Formspree endpoint daalo, tab enquiries/signups seedhe email par aayenge

## Hosting
GitHub Pages se live hai. File push karte hi site update ho jaati hai.
