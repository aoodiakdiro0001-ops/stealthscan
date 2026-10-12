# 🥷 StealthScan — Obfuscation Tester & Protector (MIT)

Measure, understand and improve YOUR OWN code's resistance to reverse
engineering. UI in EN/TR/AR. Static single file + README.
**Analyze only code you own or are authorized to audit.**

## Tools (all 100% local, code never executes)

- **📊 Strength Meter:** 0–100 score from identifier entropy, escaped
  strings, eval usage, hex-var names, string-array patterns, minification,
  comment ratio, long lines — with per-metric bars + recommendations.
- **🔍 De-obfuscator:** unescape `\x \u`, base64-string previews, `_0x`
  string-array index mapping + reference rewriting, placeholder-safe
  pretty-print. Read-only.
- **🛡️ Safe Protector (demo-grade):** comment strip, minify, hex-encode
  strings, string-array pack — all placeholder-protected and reversible.
  Verify output runs; use a maintained obfuscator for production.
- **🧩 Anti-tamper snippets:** domain lock, DevTools trap, copy-guard.

## Money & contact

- `CONFIG.ads` (AdSense/Carbon) footer slot.
- Donate: BTC + USDT-TRC20 + IBANs live.
- 📧 baranavisat@gmail.com · 📞 +90 531 326 37 22 · WhatsApp

## Run

```bash
cd stealthscan
python3 -m http.server 8080
```

## License

MIT.
