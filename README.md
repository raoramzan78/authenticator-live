# Authenticator Live — Free 2FA Code Generator (TOTP & HOTP)

Generate two-factor authentication codes online, free, with no app install and no sign-up. Codes are computed 100% in your browser — your secret key never leaves your device.

**Live site: https://get2fa.netlify.app**

## Features
- Instant TOTP codes (RFC 6238) that appear the moment you paste a key, with a live countdown ring
- HOTP counter-based codes (RFC 4226) with adjustable counter
- SHA-1, SHA-256 and SHA-512; 6 or 8 digits; custom periods
- Full otpauth:// link support, QR camera scan and QR image upload
- Click-to-copy codes, code history stored only in your own browser
- Works with Google, Amazon, Facebook, Binance, GitHub, Microsoft and every standard TOTP service

## Guides on the live site
- 2FA Authenticator Online — https://get2fa.netlify.app/2fa-authenticator-online/
- TOTP Generator — https://get2fa.netlify.app/totp-generator/
- Google Authenticator Online — https://get2fa.netlify.app/google-authenticator-online/
- How to Get a 2FA Code — https://get2fa.netlify.app/how-to-get-2fa-code/
- Amazon 2FA — https://get2fa.netlify.app/amazon-2fa/
- Facebook 2FA Code — https://get2fa.netlify.app/facebook-2fa-code/
- Binance 2FA Code — https://get2fa.netlify.app/binance-2fa-code/
- 2FA Code Not Working — https://get2fa.netlify.app/2fa-code-not-working/
- What Is 2FA? — https://get2fa.netlify.app/what-is-2fa/

## Privacy
All code generation happens locally with the Web Crypto API. No secret key is ever sent to a server. The website source is included in this repository (get2fa-v21.zip).
